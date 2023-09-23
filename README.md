# Travel_Management_Sytsem_Bus
Travel Management System, powered by Django, streamlines bus booking and management. Users can easily search for bus routes, book tickets, and administrators can efficiently manage schedules, passengers, and ticket sales through an intuitive web application

# Travel Management System by Bus

## Overview

This is a Django-based Travel Management System that allows users to search for bus schedules, book tickets, and manage their bookings. It provides a user-friendly interface for travelers to find available buses, view schedules, and book seats for their preferred routes.

## Features

- **Search for Buses**: Users can search for buses by specifying the departure location, destination, and date.

- **View Bus Schedules**: The system displays a list of available bus schedules based on the search criteria.

- **Book Tickets**: Travelers can book bus tickets by selecting a schedule and specifying the number of seats they want to book.

- **Manage Bookings**: Users can view and manage their bookings, including canceling booked tickets if needed.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/travel-management-system.git

## Getting Started

### 1. Create a Virtual Environment
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

### 2. Install Project Dependencies
    ```bash
    pip install -r requirements.txt

### 3. Apply Migrations to Set Up the Database
     ```bash
     python manage.py migrate

### 4.  Create a Superuser for Admin Access
    ```bash
    python manage.py createsuperuser

### 5. Start the Development Server
    ```bash
    python manage.py runserver

### 6. Access the Application
Access the application at http://localhost:8000.

## Usage
1. Access the application and search for available bus schedules by specifying the departure location, destination, and date.

2. View the list of available schedules and select a preferred one.

3. Book tickets by specifying the number of seats you want to book.

4. Manage your bookings, including canceling booked tickets if needed.

## Technologies Used

-Django: A high-level Python web framework for rapid development.
-SQLite: A lightweight, built-in database used for data storage.
-HTML/CSS: For building the user interface.
-JavaScript/jQuery: For interactive features.
-Bootstrap: For responsive and mobile-friendly design.

## Contributors
-Laasya Reddy M

## License
This project is licensed under the MIT License.

