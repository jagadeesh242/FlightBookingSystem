# Flight Booking System

A comprehensive console-based Flight Booking System developed in Java that allows users to manage flight bookings, passengers, and flight information.

## Project Overview

This Flight Booking System is a Java application that provides functionality for managing flight operations including passenger registration, flight booking, viewing available flights, and searching for specific routes.

## Features

- **Passenger Registration**: Register new passengers with their personal information
- **View Available Flights**: Display all available flights with their details (flight number, source, destination, and price)
- **Book Flights**: Book flights for registered passengers with travel dates
- **View Bookings**: Display all current flight bookings
- **Search Flights**: Search for flights based on source and destination
- **User-friendly Menu**: Interactive console menu for easy navigation

## Project Structure

```
FlightBookingSystem/
├── src/
│   └── com/
│       └── flightbookingsystem/
│           ├── Admin.java
│           ├── Booking.java
│           ├── Flight.java
│           ├── FlightBookingApp.java
│           ├── Passenger.java
│           ├── User.java
│           └── module-info.java
└── bin/
```

## Classes Description

### 1. FlightBookingApp.java
The main class that contains the application entry point and menu system.

### 2. Admin.java
Handles administrative functions and menu display.

### 3. Flight.java
Represents a flight with properties:
- Flight Number
- Source
- Destination
- Price

### 4. Passenger.java
Represents a passenger with properties:
- Passenger ID
- Name
- Contact Information

### 5. Booking.java
Manages flight booking information linking passengers with flights.

### 6. User.java
Represents user information and authentication.

## How to Run

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- Java IDE (Eclipse, IntelliJ IDEA, or NetBeans) or command line

### Running the Application

1. Clone the repository:
```bash
git clone https://github.com/jagadeesh242/FlightBookingSystem.git
```

2. Navigate to the project directory:
```bash
cd FlightBookingSystem
```

3. Compile the Java files:
```bash
javac FlightBookingSystem/src/com/flightbookingsystem/*.java
```

4. Run the application:
```bash
java -cp FlightBookingSystem/src com.flightbookingsystem.FlightBookingApp
```

## Menu Options

1. **Register Passenger**: Add a new passenger to the system
2. **View Available Flights**: See all flights with their details
3. **Book Flight**: Book a flight for a registered passenger
4. **View Bookings**: Display all current bookings
5. **Search Flights**: Search for flights by source and destination
6. **Exit**: Close the application

## Sample Flights

The system comes pre-loaded with sample flights:
- **AI101**: Chennai → Nepal (Rs. 6000)
- **Ek505**: Salem → Thailand (Rs. 10000)
- **AK007**: Coimbatore → America (Rs. 20000)
- **VK018**: Namakkal → Korea (Rs. 30000)

## Technologies Used

- **Language**: Java
- **Data Structures**: ArrayList
- **Input Handling**: Scanner

## Future Enhancements

- Database integration for persistent storage
- GUI implementation using JavaFX or Swing
- Payment gateway integration
- Seat selection functionality
- Booking cancellation and modification
- Email confirmation system
- Admin panel for flight management

## Author

**jagadeesh242**

## License

This project is open source and available for educational purposes.

## Contributing

Feel free to fork this repository and submit pull requests for any improvements.
