# 🎬 Movie Theater Booking System

This project is a SQL-based **Movie Theater Booking System** that allows for the management of movies, showtimes, customers, ticket bookings, and payments. It simulates the core functionalities of a cinema management system, ideal for academic use or small-scale system demos.

## 📂 Project Structure

- `Movie_Theater_Booking_System.SQL`: This file contains all SQL queries to:
  - Create the database and tables
  - Insert sample data
  - Perform basic operations like booking tickets and managing showtimes

## 🧱 Tables Overview

The system includes the following main tables:

1. **Movies**  
   Stores details about each movie (title, genre, duration, etc.)

2. **Theaters**  
   Contains theater-specific data like name, location, and capacity.

3. **Screens**  
   Each screen is linked to a theater and holds data like screen number and seating capacity.

4. **Showtimes**  
   Defines the scheduling of movies on specific screens at certain times.

5. **Customers**  
   Maintains customer information (name, contact info, etc.)

6. **Bookings**  
   Stores ticket booking data, including customer, showtime, and number of seats.

7. **Payments**  
   Handles payment information for each booking.

## ⚙️ Features

- Add new movies, theaters, screens, and showtimes
- Book tickets for customers
- Track and manage customer data
- Payment logging and tracking
- Handle seating capacity validations

## 🧪 Sample Queries

Includes pre-written queries to demonstrate:

- Inserting and updating data
- Joining multiple tables to display booking information
- Calculating revenue from bookings
- Listing available shows and their seat availability

## 🛠️ Requirements

- MySQL / PostgreSQL / any SQL-compliant RDBMS
- SQL Client (e.g., DBeaver, MySQL Workbench, pgAdmin)

## 🚀 Getting Started

1. Open your SQL environment.
2. Run the `Movie_Theater_Booking_System.SQL` script.
3. Modify or extend with your own data and queries.

## 🔧 Future Enhancements

- Add support for dynamic seat selection
- Integrate loyalty program for frequent customers
- Add admin role for showtime and movie management
- Introduce cancellation and refund logic

## 📜 License

This project is open for educational and demo purposes.
