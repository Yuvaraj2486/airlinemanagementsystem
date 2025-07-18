# Airline Reservation Management System ✈️

## Overview 🌐
The Airline Management System is a Java-based desktop application developed using Java Swing for the front-end and MySQL for the back-end database. This project simulates and manages key functionalities of an airline reservation system, including customer management, ticket booking, flight scheduling, and user authentication 🔐. Designed to provide a user-friendly interface, it automates essential airline operations efficiently.

## Features ✨
- **Admin Login** 🔑: Secure authentication for administrative access.
- **Customer Management** 👤: Add and manage customer details with ease.
- **Flight Management** ✈️: Create and schedule flights effectively.
- **Ticket Booking & Cancellation** 🎫: Handle ticket reservations and cancellations seamlessly.
- **Search Functionality** 🔍: Search for flights and customer details effortlessly.
- **Real-Time Updates** ⏱️: Syncs data in real-time with the MySQL backend.

## Installation 🛠️
### Database Setup
1. Open MySQL or any SQL client and execute the following commands:
   ```sql
   CREATE DATABASE airlinemanagementsystem;
   USE airlinemanagementsystem;

   CREATE TABLE login (
       username VARCHAR(20),
       password VARCHAR(20)
   );

   INSERT INTO login VALUES ('admin', 'admin');
   ```

### Add MySQL Connector
1. Download the MySQL Connector/J and add the JAR file to the project libraries in NetBeans:
   - Right-click on the project.
   - Choose **Properties**.
   - Go to **Libraries → Compile**.
   - Click **Add JAR/Folder** and select the MySQL Connector JAR.

### Build the Project
1. Right-click the project in NetBeans.
2. Click **Clean and Build**.

## Technology Stack ⚙️
- **Language Used**: Java
- **GUI Library**: Java Swing
- **Database**: MySQL
- **Database Connectivity**: JDBC
- **IDE Used**: NetBeans
- **Build Tool**: Apache Ant (default in NetBeans)
- **JDK Version**: Java SE 8 or later

## Usage 🚀
1. Launch the application in NetBeans after building the project.
2. Log in with the default admin credentials (username: `admin`, password: `admin`).
3. Use the GUI to manage customers, book flights, and handle cancellations.
4. Search for specific records or update flight schedules as needed.

## About 📝
A Java-based Airline Management System using Swing and MySQL, developed in NetBeans. It automates flight bookings, passenger management, payments, and cancellations with a user-friendly GUI and database integration via JDBC.

## Future Improvements 🔮
- Enhance security with encrypted passwords and role-based access.
- Add online booking capabilities via a web interface.
- Integrate payment gateways for real-time transactions.
- Improve search functionality with advanced filters.

## License 📜
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact 📬
For questions or contributions, open an issue or submit a pull request on the GitHub repository 🙌.