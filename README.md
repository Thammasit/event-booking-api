# Event Booking API

## Overview
The Event Booking API is a RESTful web service built with Symfony 7 and API Platform. It allows users to create, view, update, and delete events, as well as book tickets for these events.

## Features
- Event management (Create, Read, Update, Delete)
- Booking system for events
- Search and filter events
- Comprehensive API documentation with Swagger UI

## Prerequisites
Before you begin, ensure you have the following installed:
- PHP 8.2 or higher
- Composer
- Symfony CLI
- Docker (optional, for containerized environment)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Thammasit/event-booking-api.git
   cd event-booking-api
2. Install dependencies:
   composer install
3. Set up the environment variables:
  cp .env .env.local
# Update .env.local with your database and other configurations
4. Set up the database:
  symfony console doctrine:database:create
  symfony console doctrine:migrations:migrate

Usage
Running the Application
To start the application, run:
symfony serve

Accessing the API
The API is accessible at:
http://localhost:8000/api

API Documentation
API Platform provides an in-browser tool to explore the API endpoints and their documentation. You can access it at:
http://localhost:8000/api

