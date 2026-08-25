# Flight Reservation System Using Dijkstra's Algorithm

![Flight Reservation System](https://github.com/user-attachments/assets/aac9b4ec-56d8-45bb-b454-9e27a320864f)

## Introduction

With the increasing popularity of air travel, finding convenient, affordable, and efficient flight routes has become increasingly important. Travelers often consider several factors when choosing a flight, including **travel time, cost, number of layovers, and overall convenience**.

This project is a **console-based Flight Reservation System** designed to help users find efficient routes between airports by applying **Dijkstra's Algorithm**. The system represents airports and flights as a graph and calculates the shortest or most cost-effective route based on the selected criteria.

The main objective of this project is to provide users with an easy-to-use system for searching flights, comparing available routes, viewing flight details, and making reservations.

## Data Structures and Algorithms

The project primarily uses **Graphs** to represent the flight network.

- **Vertices (Nodes):** Represent airports.
- **Edges:** Represent direct flights between airports.
- **Edge Weights:** Represent factors such as flight cost or travel time.
- **Dijkstra's Algorithm:** Used to find the shortest or most efficient route between two airports.

Additional data structures may also be used where appropriate, such as:

- **Lists/Vectors** for storing flights, airports, and passenger information.
- **Hashing** for efficient searching and retrieving airport or flight information.
- **Priority Queue** for efficiently implementing Dijkstra's Algorithm.
- **Classes and Objects** for organizing the different components of the reservation system.

## Main Features

### 1. Real-World Airlines and Airports

The system can include real-world airlines and airports to provide users with a realistic flight-booking experience.

### 2. Multiple Travel Classes

Users can select different travel classes according to their preferences, such as:

- Economy Class
- Premium Economy
- Business Class
- First Class

Different classes may have different fares and available services.

### 3. Flight Search and Reservation

Users can search for available flights by entering information such as:

- Departure airport
- Destination airport
- Preferred airline
- Travel class

After selecting a suitable route, users can make a reservation through the system.

### 4. Shortest and Most Efficient Route

The system uses **Dijkstra's Algorithm** to determine an efficient route between the selected departure and destination airports.

Depending on the implementation, the system can calculate routes based on:

- Minimum cost
- Minimum travel time
- Shortest route

### 5. Flight Details

The system displays important information about available flights, including:

- Flight number
- Airline
- Departure airport
- Destination airport
- Departure and arrival times
- Ticket price
- Travel class
- Layover information
- Total travel time

### 6. Reservation Management

Users can create and manage their flight reservations. The system may provide options such as:

- Making a reservation
- Viewing reservation details
- Searching for a reservation
- Cancelling a reservation

### 7. User-Friendly Console Interface

The application provides a simple and user-friendly **console-based interface** that allows users to navigate through different options and perform flight-related operations easily.

## Project Objectives

The main objectives of this project are:

1. To implement a real-world application of **Graph data structures**.
2. To understand and implement **Dijkstra's shortest-path algorithm**.
3. To develop a basic flight reservation system using **Object-Oriented Programming (OOP)**.
4. To provide users with efficient flight route searching.
5. To demonstrate the practical use of data structures and algorithms in a real-world scenario.

## Technologies Used

- **Programming Language:** C++
- **Data Structure:** Graph
- **Algorithm:** Dijkstra's Algorithm
- **Programming Paradigm:** Object-Oriented Programming (OOP)
- **Interface:** Console-based application

## Future Enhancements

Additional features can be added as the project develops, such as:

- User login and registration
- Seat selection
- Different baggage allowances
- Flight cancellation and rescheduling
- Dynamic ticket pricing
- Multiple route comparison
- Passenger management
- File handling for saving reservations
- Admin panel for managing flights and airports

## Conclusion

The Flight Reservation System demonstrates how **graphs and Dijkstra's Algorithm** can be applied to a practical real-world problem. By representing airports and flights as a weighted graph, the system can efficiently determine suitable routes between destinations.

The project also provides an opportunity to apply **Object-Oriented Programming, data structures, algorithms, and file handling** in the development of a complete console-based application.