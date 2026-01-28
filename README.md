# library-management-system-java-oracle
A robust desktop-based application built to digitize manual library operations. This system integrates a Java Swing GUI with an Oracle SQL database to manage books, readers, and staff efficiently.
Key Features:
Authentication: Admin login with secure credential verification.
Book Management: Add, update, and delete book records with real-time status tracking.
Reader & Staff Directory: Centralized database to manage profiles and contact details.
Issue & Return Workflow: Automated tracking of book circulation with issue/return date logging.
Database Statistics: Real-time data retrieval for analytical reporting of library assets.

Technical Stack:
Frontend: Java Swing (GUI)
Backend: Oracle SQL (Relational Database)
Connectivity: JDBC (Java Database Connectivity)
IDE: Eclipse / Oracle SQL Developer

System Architecture:
The application follows a standard Client-Server Architecture:
Client (GUI): Handles user interactions and form inputs.
Bridge (JDBC): Managed data flow and SQL query execution.
Database (Oracle SQL): Stores persistent data in normalized relational tables.
Project Team & Contributions
This project was a collaborative effort at Fatima Jinnah Women University.
Nashra Azhar: Developed the GUI Framework, implemented the Issue/Return Modules, and managed the JDBC connection logic.
Fizzah Rafiq & Humna Sheraz: Designed the Oracle SQL Schema, implemented Sequences, and developed the Staff Management module.
