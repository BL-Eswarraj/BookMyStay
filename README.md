#  BookMyStayApp

**A Java Console-Based Hotel Booking Management System that demonstrates Core Java, Object-Oriented Programming, Collections Framework, Data Structures, and Algorithm concepts through real-world hotel booking scenarios.**

</div>
---

# Project Overview

**BookMyStayApp** is a console-based hotel booking management application that simulates the complete booking lifecycle of a hotel reservation system.

The project is developed to help learners understand **Core Java** concepts by implementing real-world hotel booking operations such as customer registration, room booking, room availability, payment tracking, booking history, and reporting.

The application gradually introduces Java concepts through multiple incremental use cases.

---

# Project Objectives

The primary objectives of this project are:

- Learn Object-Oriented Programming
- Understand Java Collections Framework
- Practice Data Structures
- Implement Searching & Sorting Algorithms
- Learn Exception Handling
- Understand File Handling
- Practice Clean Code Principles
- Simulate Real-world Booking Systems

---

# Features

## Hotel Management

- Add Hotel Rooms
- View Rooms
- Search Rooms
- Update Room Status

---

## Customer Management

- Register Customers
- View Customers
- Search Customers

---

## Booking Management

- Book Room
- Cancel Booking
- Booking History
- Booking Reports

---

## Room Management

- Deluxe Rooms
- Suite Rooms
- Standard Rooms

---

## Reports

- Booking Summary
- Occupancy Report
- Customer Report
- Booking History

---

# Technologies Used

- Java 17+
- Core Java
- OOP
- Collections Framework
- Java Streams
- IntelliJ IDEA
- Git
- GitHub

---

# Project Architecture

```
                  User

                    │

              Console Menu

                    │

      ----------------------------

      │            │            │

 Customer     Booking       Room

      │            │            │

      ------------Service--------

                    │

             Java Collections
```

---

# Project Structure

```
BookMyStayApp
│
├── src
│
├── model
│      Customer.java
│      Room.java
│      Booking.java
│
├── service
│      BookingService.java
│      CustomerService.java
│      RoomService.java
│
├── util
│      ValidationUtil.java
│
├── BookMyStayApp.java
│
├── README.md
│
└── .gitignore
```

---

#  Features Covered

## Customer Registration

- Register Customers
- Unique Customer ID
- Customer Details

---

## Room Management

- Add Rooms
- Display Rooms
- Room Categories
- Room Availability

---

## Booking

- Create Booking
- Cancel Booking
- Booking Status

---

## Reports

- Booking History
- Customer Reports
- Room Reports

---

#  Java Concepts Covered

## Core Java

- Classes
- Objects
- Constructors
- Packages
- Access Modifiers
- Enums

---

## Object-Oriented Programming

- Encapsulation
- Abstraction
- Inheritance
- Polymorphism
- Composition

---

## Java Collections

- ArrayList
- LinkedList
- HashSet
- LinkedHashSet
- TreeSet
- HashMap
- TreeMap

---

## Java Stream API

- stream()
- filter()
- map()
- collect()
- reduce()
- sorted()
- groupingBy()
- forEach()

---

## Algorithms

### Sorting

- Bubble Sort
- Arrays.sort()
- Comparator

### Searching

- Linear Search
- Binary Search

---

## Exception Handling

- try
- catch
- finally
- throw
- throws
- Custom Exceptions

---

## File Handling

- FileReader
- BufferedReader
- CSV File Reading

---

## Validation

- Regular Expressions
- Input Validation
- Business Rule Validation

---

# Learning Outcomes

After completing this project, you will understand:

- Core Java
- Object-Oriented Programming
- Java Collections Framework
- Stream API
- Exception Handling
- Searching Algorithms
- Sorting Algorithms
- Defensive Programming
- Clean Code Practices

---

# Sample Console Flow

```
===============================
      BOOK MY STAY APP
===============================

1. Customer Registration
2. Room Booking
3. View Rooms
4. Booking History
5. Reports
6. Exit
```

---

# Modules

## Customer Module

- Customer Registration
- Customer Details
- Search Customer

---

## Room Module

- Room Availability
- Room Booking
- Room Categories

---

## Booking Module

- Create Booking
- Cancel Booking
- Booking History

---

## Report Module

- Booking Reports
- Customer Reports
- Occupancy Reports

---

## Open Project

Open the project using:

- IntelliJ IDEA
- Eclipse

---

## Compile

```bash
javac BookMyStayApp.java
```

---

## Run

```bash
java BookMyStayApp
```

---

# Future Enhancements

- Spring Boot REST APIs
- MySQL Database
- Hibernate ORM
- Spring Data JPA
- JWT Authentication
- Spring Security
- Payment Gateway
- Email Notifications
- Docker Support
- Kafka Notifications
- Microservices Architecture
- React Frontend
- Admin Dashboard
- Online Booking Portal

```bash
git checkout -b feature/new-feature
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push the branch

```bash
git push origin feature/new-feature
```

5. Create a Pull Request
