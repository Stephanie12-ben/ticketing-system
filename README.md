Real-Time Ticketing System


Project Overview
The Real-Time Ticketing System is a dynamic and scalable solution for managing ticket sales in real-time. It enables users to purchase tickets, tracks the number of available tickets, and logs all system activities, ensuring smooth operation and data integrity. This system uses a combination of React for the frontend and Spring Boot for the backend, with MySQL for database management.

Features
Configuration Management: Set parameters such as total tickets, ticket release rate, and pool size.
Real-Time Ticket Purchase: Purchase tickets in real-time with updates to the ticket pool.
System Logging: Maintain logs for all activities, including ticket purchases and system state changes.
Scalable Backend: Built using Spring Boot for seamless integration with MySQL.
Interactive Frontend: Developed with React to provide a user-friendly interface.

Technologies Used
Frontend
React: User Interface
JavaScript: Component logic
CSS: Styling

Backend
Spring Boot: RESTful API and server-side logic
MySQL: Database management

Tools
Postman: API testing
npm: Package management

Installation and Setup
Prerequisites
Node.js and npm installed
Java (JDK 22) installed
MySQL server set up

Frontend Setup
Navigate to the frontend directory:
   cd frontend
Install dependencies:
   npm install
Start the React development server:
   npm start

Backend Setup
Navigate to the backend directory:
   cd backend
Build and run the Spring Boot application:
   ./mvnw spring-boot:run
Database Setup
   Create a database named ticket_system.

Configure database credentials in the application.properties file:

spring.datasource.url=jdbc:mysql://localhost:3306/ticket_system
spring.datasource.username=root
spring.datasource.password=" "

Run the application to initialize the database.

Usage
Configuration
Open the application in your browser.
Fill out the configuration form with required parameters.
Save the configuration.
Ticket Management
Use the "Purchase Tickets" section to buy tickets.
Monitor the remaining tickets in real-time.
Logging
Check the system logs displayed in the UI for activity updates.
API Endpoints
GET /api/tickets: Fetch available tickets.
POST /api/purchase: Purchase specified tickets.

Future Enhancements
Add authentication and authorization.
Support for multiple ticket categories.
Integration with payment gateways.

Contributors
Developer: [Benedict Stephanie]
Project Manager: [Benedict Stephanie]
UI Designer: [Benedict Stephanie]


Acknowledgments
Inspired by real-time systems and scalable architecture principles.



### Steps to run the project:
1. Clone this repository:
   ```bash
   git clone https://github.com/Stephanie12-ben/ticketing-system.git
