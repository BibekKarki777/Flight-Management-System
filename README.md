# Flight Management System

A Java-based Flight Management System developed using Object-Oriented Programming principles. This project supports flight, customer, passenger, and booking management through both a command-line interface and a Java Swing graphical user interface.

## About the Project

The Flight Management System is designed to manage basic airline booking operations. Administrators can manage flights, customers, and bookings, while passengers can register, log in, search for flights, book flights, view their profile, and manage their bookings.

This project demonstrates core Java concepts such as classes, objects, inheritance, encapsulation, exception handling, collections, file handling, GUI development, authentication, and unit testing.

## Features

### Admin Features

- Admin login
- Add new flights
- View available flights
- Search flights
- Update flight details
- Soft delete flights
- Add customer records
- View customer details
- Delete customer records
- Issue bookings for customers
- Cancel bookings
- Update or rebook flights
- View booking information
- View dynamic pricing details

### Passenger Features

- Passenger registration
- Passenger login
- Search available flights
- Book flights
- Cancel bookings
- Update bookings
- View booking history
- View profile information
- Logout functionality

### Booking and Pricing Features

- Create flight bookings
- Cancel existing bookings
- Rebook to another flight
- Prevent overbooking when flight capacity is full
- Calculate cancellation and rebooking fees
- Dynamic pricing based on booking date, flight demand, and weekend travel
- File-based data storage for flights, customers, bookings, and users

### GUI Features

- Welcome screen
- Admin login page
- Passenger login and registration pages
- Admin dashboard
- Passenger dashboard
- Flight management windows
- Customer management windows
- Booking management windows
- Search flight interface

## Tech Stack

- Java
- Java Swing
- Object-Oriented Programming
- File Handling
- Collections Framework
- Exception Handling
- JUnit 5
- Eclipse IDE
- Git and GitHub

## Project Structure

```text
Flight-Management-System/
├── src/
│   └── bcu/
│       └── cmp5332/
│           └── bookingsystem/
│               ├── commands/
│               ├── data/
│               ├── gui/
│               ├── main/
│               ├── model/
│               ├── services/
│               ├── test/
│               └── util/
├── resources/
│   └── data/
│       ├── bookings.txt
│       ├── customers.txt
│       ├── flights.txt
│       └── users.txt
├── doc/
├── README.md
├── .classpath
└── .project
```

## Main Packages

### commands

Contains command classes used by the command-line interface, such as adding flights, listing customers, issuing bookings, cancelling bookings, updating bookings, and loading the GUI.

### data

Handles loading and saving data from text files, including flight data, customer data, booking data, and user data.

### gui

Contains Java Swing windows for the admin portal, passenger portal, login, registration, flight management, customer management, and booking management.

### main

Contains the main application entry point and command parser.

### model

Contains the main business objects such as Flight, Customer, Booking, User, Role, Session, and pricing-related classes.

### services

Contains authentication-related logic.

### test

Contains JUnit test classes for checking the main system functionality.

### util

Contains helper classes such as password hashing and validation utilities.


## Data Storage

This project uses file-based persistence. Data is stored inside the `resources/data` folder:

- `flights.txt` stores flight records
- `customers.txt` stores customer records
- `bookings.txt` stores booking records
- `users.txt` stores user login records

## Testing

The project includes JUnit test classes inside the `test` package. These tests check important system components such as flights, customers, bookings, pricing, and the main flight booking system logic.

## Author

**Bibek Karki**

- GitHub: [BibekKarki777](https://github.com/BibekKarki777)
- LinkedIn: [Bibek Karki](https://www.linkedin.com/in/bibekkarkinp/)

## License

This project is created for academic and learning purposes.
