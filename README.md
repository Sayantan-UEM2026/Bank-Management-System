Bank Management System
A Java-based desktop application providing core banking operations (deposit, withdrawal, balance enquiry, user registration, etc.) with a clean Swing GUI and MySQL database integration.

Project Structure
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
│   ├── mysql

Key Modules:
  BalanceEnquiry: View current account balance.
  Deposit: Add funds to user account.
  Withdrawl: Withdraw funds from the account.
  Signup / Signup2 / Signup3: Multi-step new user registration.
  Login: User authentication system.
  Con: Handles database connection (MySQL via JDBC).
  main_Class: Main controller/entry point for app execution.
  icon: Folder containing resource files for UI.
  jcalendar-tz-1.3.3-4.jar: Calendar/date library for GUI forms.
  mysql-connector-java-8.0.28.jar: MySQL JDBC driver.

Technologies Used:
  Java Swing (GUI)
  JDBC (Database connection)
  MySQL (Database)
  JCalendar (Date inputs)
  Git (Version control)




