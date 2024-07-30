
# Car Rental System

This project implements a car rental system in Java. It allows customers to rent and return cars, keeping track of available and rented cars. The system provides a command-line menu for user interaction.

## Features

- **Add Cars:** Add new cars to the rental system.
- **Rent Cars:** Rent available cars to customers.
- **Return Cars:** Return rented cars.
- **View Rental Information:** Display details of rental transactions.

## Object-Oriented Programming (OOP) Concepts

This project demonstrates the following OOP concepts:

1. **Encapsulation:**
   - Each class (Car, Customer, Rental, CarRentalSystem) encapsulates its data and provides methods to interact with that data. For example, the Car class encapsulates car attributes and provides methods to rent and return the car.

2. **Abstraction:**
   - The classes provide a clear interface for interacting with different parts of the system. The details of how each class works internally are hidden from the user. For example, the CarRentalSystem class provides methods to rent and return cars without exposing the internal list of cars and rentals.

3. **Inheritance:**
   - Although not explicitly used in this project, the design of the classes allows for easy extension. For example, a subclass of Car could be created for different types of cars (e.g., SUV, Sedan) with additional attributes and methods.

4. **Polymorphism:**
   - Polymorphism is not explicitly used in this project, but the design allows for potential future enhancements where different types of cars or customers could be handled using a common interface.

## Classes

- **Car:** Represents a car with attributes like car ID, brand, model, base price per day, and availability status.
- **Customer:** Represents a customer with attributes like customer ID and name.
- **Rental:** Represents a rental transaction with attributes like the rented car, customer, and rental days.
- **CarRentalSystem:** Manages the list of cars, customers, and rentals. Provides methods to add cars, add customers, rent cars, return cars, and display a menu for user interaction.
- **Main:** The main class to initialize the system and start the menu.

## How to Run

1. Clone the repository.
2. Compile the Java files.
3. Run the `Project` class to start the system.

## Example Usage

1. Rent a Car: 
   - Enter your name.
   - Select an available car by its ID.
   - Enter the number of rental days.
   - Confirm the rental.

2. Return a Car:
   - Enter the car ID to return.
   - The system will mark the car as available and remove the rental record.
  
   # Display
<img width="550" alt="1" src="Screenshot (16).png">   
