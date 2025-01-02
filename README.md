# Airline Management System

The *Airline Management System* is a Java-based application designed to manage various aspects of airline operations, including flight details, customer information, ticket booking, journey details, and ticket cancellation. This system provides a user-friendly interface for both administrators and customers to interact with the airline's database efficiently.

## Features

- *Flight Information Management*: View and manage flight details such as flight name, code, source, destination, and date.
- *Customer Management*: Add and manage customer details including name, nationality, address, and contact information.
- *Ticket Booking*: Book flights for customers by selecting source, destination, and travel date.
- *Journey Details*: Retrieve journey details using the PNR (Passenger Name Record) number.
- *Ticket Cancellation*: Cancel booked tickets and generate cancellation details.
- *Boarding Pass*: Generate boarding passes for passengers using their PNR number.
- *User  Authentication*: Secure login system for administrators to access the system.

## Technologies Used

- *Java*: Core programming language used for backend logic.
- *Swing*: Used for creating the graphical user interface (GUI).
- *MySQL*: Database management system for storing flight, customer, and booking details.
- *JDBC*: Java Database Connectivity for interacting with the MySQL database.
- *NetBeans*: Integrated Development Environment (IDE) used for development.

## Prerequisites

Before running the application, ensure you have the following installed:

- *Java Development Kit (JDK)*: Version 8 or higher.
- *MySQL Server*: To host the database.
- *MySQL Connector/J*: JDBC driver for MySQL.
- *NetBeans IDE*: Optional, but recommended for development and debugging.

## Installation and Setup

1. *Clone the Repository*:

   
   git clone https://github.com/your-username/AirlineManagementSystem.git
   cd AirlineManagementSystem
   
   
2. *Database Setup*:
   - Import the provided SQL file (
     airlinemanagementsystem.sql
     

     ) into your MySQL server to create the necessary database and tables.
   - Update the database connection details in the 
 Conn.java
     

      file located in the 
     airlinemanagementsystem
     

      package.
3. *Run the Application*:
   - Open the project in NetBeans IDE.
   - Build and run the project from the IDE.
   - Alternatively, you can compile and run the project using the command line:
     javac airlinemanagementsystem/*.java
     java airlinemanagementsystem.Login
     
     

## Usage

1. *Login*:
   - Launch the application and log in using the provided credentials.
2. *Home Screen*:
   - After logging in, you will be directed to the home screen where you can access various features such as flight details, customer management, ticket booking, etc.
3. *Flight Details*:
   - View all available flights and their details.
4. *Customer Management*:
   - Add new customers or update existing customer details.
5. *Ticket Booking*:
   - Book tickets for customers by selecting the flight, source, destination, and travel date.
6. *Journey Details*:
   - Retrieve journey details using the PNR number.
7. *Ticket Cancellation*:
   - Cancel booked tickets and generate cancellation details.
8. *Boarding Pass*:
   - Generate boarding passes for passengers using their PNR number.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

1. *Fork the Repository*:
   - Fork the repository to your own GitHub account.
2. *Clone the Forked Repository*:

   
   git clone https://github.com/xrishis/AirlineManagementSystem.git
   cd AirlineManagementSystem
   
   
3. *Create a New Branch*:

   
   git checkout -b feature/your-feature-name
   
   
4. *Commit Your Changes*:
git add .
   git commit -m "Add your commit message here"
   
   
5. *Push to the Branch*:

   
   git push origin feature/your-feature-name
   
   
6. *Open a Pull Request*:
   - Go to the original repository and open a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](https://www.blackbox.ai/chat/LICENSE) file for more details.

## Acknowledgments

- *Java Swing*: For providing the GUI framework.
- *MySQL*: For the robust database management system.
- *NetBeans*: For the comprehensive IDE that made development easier.

## Contact

For any inquiries or support, please contact:

- *Your Name*: Rishi [rishirajnachiketa@gmail.com]
- *GitHub*: xrishis
