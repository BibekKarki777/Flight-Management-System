# Flight Management System

A Java-based Flight Management System developed using Object-Oriented Programming principles. This project allows users to manage flights, customers, and bookings through both a command-line interface and a graphical user interface.

## Project Overview

The Flight Management System is designed to support basic airline booking operations. It allows administrators to manage flight records, customer details, and booking information, while passengers can register, log in, view available flights, and manage their bookings.

The project demonstrates the use of Java OOP concepts such as classes, objects, inheritance, encapsulation, collections, exception handling, file handling, and GUI development.

## Features

### Admin Features

- Admin login
- Add new flights
- View available flights
- Update flight details
- Delete or remove flights
- Add customer records
- View customer details
- Delete customer records
- Issue bookings for customers
- Cancel bookings
- Update bookings
- View booking information

### Passenger Features

- Passenger registration
- Passenger login
- View available flights
- Book flights
- View personal booking history
- View profile information
- Logout functionality

### Booking Features

- Create flight bookings
- Cancel existing bookings
- Update booking details
- Track customer bookings
- Prevent overbooking when flight capacity is full
- Store booking information using file-based persistence

### GUI Features

- Welcome screen
- Admin login page
- Passenger login/register page
- Admin dashboard
- Passenger dashboard
- Flight management pages
- Customer management pages
- Booking management pages

## Technologies Used

- Java
- Java Swing
- Object-Oriented Programming
- File Handling
- Collections Framework
- Exception Handling
- Command-Line Interface
- Git and GitHub

## Project Structure

```text
FlightBookingSystem/
│
├── src/
│   └── bcu/
│       └── cmp5332/
│           └── bookingsystem/
│               ├── commands/
│               ├── data/
│               ├── gui/
│               ├── main/
│               └── model/
│
├── resources/
│   └── data/
│       ├── flights.txt
│       ├── customers.txt
│       └── bookings.txt
│
├── README.md
└── .gitignore
