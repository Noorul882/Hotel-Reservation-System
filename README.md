# Hotel Reservation System

## Overview

`HotelReservationSystem` is a Java application that enables users to manage hotel room reservations. The application allows users to search for available rooms, make reservations, and view booking details. It includes features for room management, reservation processing, and payment simulation.

## Features

- **Room Management:** Initializes and manages rooms with different categories and prices.
- **Room Search:** Allows users to search for available rooms based on category.
- **Reservation:** Facilitates making reservations by selecting a room, entering guest details, and specifying the number of nights.
- **Payment Simulation:** Simulates payment processing with options for Credit Card and Debit Card.
- **Booking Details:** Provides a summary of all current reservations.

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- A command-line interface (CLI) for running the Java application

## Installation

1. Clone this repository to your local machine using Git:
   ```sh
   git clone https://github.com/yourusername/HotelReservationSystem.git

2. Navigate to the project directory:
   cd HotelReservationSystem


## Usage

1. Compile the Java Program:
   javac HotelReservationSystem.java

2. Run the Compiled Java Program:
   java HotelReservationSystem

3. Interact with the System:
   -Search Available Rooms: Choose option 1 and enter the room category (Single, Double, Suite).
   -Make a Reservation: Choose option 2, enter the guest name, room number, and number of nights.
   -View Booking Details: Choose option 3 to view a summary of all reservations.
   -Exit: Choose option 4 to exit the system

## Example

--- Hotel Reservation System ---
1. Search Available Rooms
2. Make a Reservation
3. View Booking Details
4. Exit
Enter your choice: 1
Enter room category to search (Single, Double, Suite): Suite

Available rooms in category Suite:
Room 201 (Suite) - Available - $250.0
Room 202 (Suite) - Available - $250.0

--- Hotel Reservation System ---
1. Search Available Rooms
2. Make a Reservation
3. View Booking Details
4. Exit
Enter your choice: 2
Enter guest name: John Doe
Enter room number to reserve: 201
Enter number of nights: 3

Reservation made successfully.
Reservation: John Doe - Room 201 (Suite) - 3 nights - Total: $750.0

Processing payment of $750.0 using CreditCard...
Payment successful.

--- Hotel Reservation System ---
1. Search Available Rooms
2. Make a Reservation
3. View Booking Details
4. Exit
Enter your choice: 3

Booking details:
Reservation: John Doe - Room 201 (Suite) - 3 nights - Total: $750.0

## Error Handling
   -Invalid Payment Method: If an invalid payment method is entered, the payment will fail.
   -Room Not Available: If the selected room is not available, the system will notify the user.
