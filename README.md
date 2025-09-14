🏦 Bank Management System

A Java-based desktop application providing core banking operations such as deposit, withdrawal, balance enquiry, and user registration. The system is built with a clean Swing GUI and integrates with a MySQL database using JDBC.

📑 Table of Contents

Project Structure

Key Modules

Features

Installation and Setup

Technologies Used

Screenshots

Author

📂 Project Structure
Bank Management System/
├── .idea/
├── out/
├── src/
│   └── bank.management.system/
│       ├── icon/
│       ├── BalanceEnquiry.java
│       ├── Con.java
│       ├── Deposit.java
│       ├── Login.java
│       ├── main_Class.java
│       ├── Signup.java
│       ├── Signup2.java
│       ├── Signup3.java
│       ├── Withdrawl.java
│   ├── icon/
│   ├── jcalendar-tz-1.3.3-4.jar
│   ├── Main.java
│   ├── mysql-connector-java-8.0.28.jar

🔑 Key Modules

BalanceEnquiry.java → View current account balance

Deposit.java → Deposit funds into the account

Withdrawl.java → Withdraw funds from the account

Signup / Signup2 / Signup3.java → Multi-step new user registration process

Login.java → User authentication system

Con.java → Database connection handler (MySQL via JDBC)

main_Class.java → Main controller / entry point for the application

icon/ → Resource files (images/icons for GUI)

jcalendar-tz-1.3.3-4.jar → Calendar/date input library for GUI forms

mysql-connector-java-8.0.28.jar → MySQL JDBC driver

✨ Features

📝 User Registration (multi-step form with validations)

🔐 User Login & Authentication

💰 Deposit Funds securely

💸 Withdraw Funds with balance validation

📊 Balance Enquiry with real-time updates from DB

🖥️ Interactive GUI built with Java Swing

🗄️ Persistent Data Storage using MySQL database

⚙️ Installation and Setup
Prerequisites

Java JDK 8+

MySQL Server (with a database named bankmanagement)

IntelliJ IDEA / Eclipse (or any Java IDE)

MySQL JDBC Driver (already included in project: mysql-connector-java-8.0.28.jar)

Steps

Clone the repository:

git clone https://github.com/your-username/Bank-Management-System.git


Set up MySQL database:

CREATE DATABASE bankmanagement;
USE bankmanagement;

CREATE TABLE account (
    account_no INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(50),
    dob DATE,
    address VARCHAR(100),
    balance DOUBLE
);

Open project in IDE IntelliJ.

Add JAR dependencies (if not already linked):

mysql-connector-java-8.0.28.jar

jcalendar-tz-1.3.3-4.jar

Run the application:
Execute main_Class.java.

🛠️ Technologies Used

Java Swing → GUI Development

JDBC → Database Connectivity

MySQL → Database Management

JCalendar → Date Picker for forms

Git → Version Control

📸 Screenshots

<img width="1907" height="1016" alt="image" src="https://github.com/user-attachments/assets/299dc8b7-74cb-4d18-92b1-40800db48c91" />
<img width="1902" height="1016" alt="image" src="https://github.com/user-attachments/assets/e84e0247-5e9d-4516-b1e7-551f91d7d09b" />



👨‍💻 Author

Sayantan Sadhukhan
