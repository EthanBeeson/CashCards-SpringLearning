# Cash Card Application

## Description

This project is a Cash Card Application built using Spring Boot, as part of the Spring Learning tutorial. 
The application simulates a cash card system where users can check their balance, add funds, and make transactions.

## Features

- User authentication
- Balance checking
- Fund adding
- Transaction history

## Getting Started

### Prerequisites

- Java 11 or higher
- Maven 3.6 or higher (for dependency management)
- IDE with Spring Boot support (e.g., IntelliJ IDEA, Eclipse)

### Installation
- cd cashcard-application
- mvn clean install
- mvn spring-boot:run
- Access the application in your browser at http://localhost:8080.

### Database Setup
- This application uses a small test database, to test with bigger databases ensure that the
  database schema is set up correctly. You might need to run database migration scripts.

### Usage
 1. User Registration: Register a new user through the registration endpoint.
 2. Login: Log in using the registered credentials.
 3. Check Balance: Use the balance endpoint to view your current balance.
 4. Add Funds: Add funds to your cash card via the appropriate endpoint.
 5. Transaction History: View a history of transactions made with your cash card.

### API Endpoints
 - `POST /api/register` - Register a new user
 - `POST /api/login` - Log in to the application
 - `GET /api/balance` - Get current balance
 - `POST /api/addFunds` - Add funds to your card
 - `GET /api/transactions` - Get transaction history

### License
This project and the code within is code that I have written after following a tutorial from Spring.io
The spring.io learning resource for teaching and learning spring and specifically spring boot.
