
# Project Formulation & Initial Requirements

## Project Overview

For this project, I will be developing a simplified ride-sharing system inspired by BlaBlaCar. The platform will allow users to register as either drivers or passengers. Drivers can post available rides, including the destination, date, and time, while passengers can search for and book a ride that suits their schedule. The platform will handle login functionality for both drivers and passengers, ensuring secure access to the system’s resources.

This project will implement essential features like user authentication, ride management, and role-based access to resources, making it a great fit for exploring .NET development concepts such as web applications, RESTful APIs, and object-relational mapping (ORM).

## Project Domain

The ride-sharing industry has grown rapidly, offering eco-friendly and cost-effective transportation alternatives. This simplified version of a ride-sharing platform will aim to provide a user-friendly experience where people can easily find or offer rides for both short and long distances.

## Requirements (User Stories)

### As a Driver:
- I want to be able to create an account so that I can manage my rides.
- I want to log in to the platform to access my profile and rides.
- I want to post a ride with details like destination, date, and time.
- I want to be able to edit or delete my ride if plans change.
  
### As a Passenger:
- I want to create an account so I can book rides.
- I want to log in to the platform to view my booking history.
- I want to search for available rides based on destination and time.
- I want to book a ride with a driver and receive confirmation.

### General:
- The system must allow different roles (drivers and passengers) to access their respective resources.
- The system must securely store user data using an ORM and SQLite.
