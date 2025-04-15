# Database-Systems_SQL
Database design and implementation for a private hospital in the UK. Project includes entity relationship modeling, SQL scripts for table creation and data manipulation, database normalization (1NF, 2NF, 3NF), and discussion of security, integrity, and ethical considerations.
# Hospital Database Management System

## Overview

This project documents the design and implementation of a database system for a small private hospital located in the West Midlands, UK. [cite: 2, 3, 4] The database addresses the challenges of managing patient records, appointments, staff information, and other hospital operations efficiently. [cite: 3, 4]

## Features

* **Entity-Relationship (ER) Modeling:** The database schema is designed using an ER model created with Oracle SQL Data Modeller. [cite: 10, 18]
* **Database Normalization:** The database is normalized up to 3NF to minimize data redundancy and ensure data integrity. [cite: 62, 63, 64, 65]
* **SQL Implementation:** SQL scripts are provided for creating tables, defining constraints, populating the database, and performing data queries using Oracle Live SQL. [cite: 18]
* **Data Management:** The database manages core hospital entities, including:
    * Patients [cite: 27]
    * Staff [cite: 27]
    * Appointments [cite: 27]
    * Departments [cite: 27]
    * Medications [cite: 27]
    * Rooms [cite: 27]
* **Security and Ethics:** The project emphasizes database security, data integrity, and ethical considerations for handling sensitive patient and staff data, addressing aspects like GDPR compliance. [cite: 119, 120, 121]

## Project Structure

The project is organized as follows:

* **[Project Report File Name].pdf:** The main project report document, detailing the database design, implementation, and analysis.
* **sql/:** (Optional - If you have separate SQL files) This directory contains the SQL scripts for creating and populating the database.
* **erd/:** (Optional - If you have ERD files) This directory contains the Oracle SQL Data Modeller files or exported ER diagrams.

## Technologies Used

* Oracle SQL Data Modeller [cite: 10, 18]
* Oracle Live SQL [cite: 18]

## Database Design

The database consists of six entities:

* **Patient:** Stores patient demographics, medical history, and contact information. [cite: 27, 28, 29, 30, 31]
* **Staff:** Stores staff details, job information, and contact information. [cite: 27, 28, 29, 30, 31]
* **Appointment:** Manages appointment schedules and details. [cite: 27, 28, 29, 30, 31]
* **Department:** Stores department information. [cite: 27, 28, 29, 30, 31]
* **Medication:** Stores medication details. [cite: 27, 28, 29, 30, 31]
* **Room:** Manages room allocation and details. [cite: 27, 28, 29, 30, 31]

Key relationships between entities are defined, including:

* Patient - Staff (Many-to-Many) [cite: 38, 39, 40, 41, 42, 43, 44, 45]
* Patient - Appointment (One-to-Many) [cite: 38, 39, 40, 41, 42, 43, 44, 45]
* Patient - Room (One-to-One / One-to-Many) [cite: 38, 39, 40, 41, 42, 43, 44, 45]
* Patient - Medication (One-to-Many / One-to-One) [cite: 46, 47, 48, 49, 50, 51, 52]
* Staff - Department (One-to-One / One-to-Many) [cite: 46, 47, 48, 49, 50, 51, 52]
* Staff - Appointment (One-to-Many / One-to-One) [cite: 46, 47, 48, 49, 50, 51, 52]
* Staff - Medication (One-to-Many / One-to-One) [cite: 46, 47, 48, 49, 50, 51, 52]

## Normalization

The database normalization process involved transforming the initial unnormalized table into 3rd Normal Form (3NF) to eliminate data redundancy and improve data integrity. [cite: 62, 63, 64, 65, 66, 67] The normalization process is detailed in the project report. [cite: 62, 63, 64, 65, 66, 67]

## SQL Implementation

SQL DDL (Data Definition Language) statements were used to create the database tables, and DML (Data Manipulation Language) statements were used to insert, query, and update data. [cite: 87, 88, 89, 90, 91]

## Security, Integrity, and Ethics

The project addresses critical aspects of data security, integrity, and ethical considerations, including:

* **Security:** Encryption, access controls, authentication, audit logging, data masking, backups, and disaster recovery. [cite: 120, 121, 122, 123, 124, 125, 126, 127]
* **Integrity:** Validation rules, referential integrity, normalization, transaction integrity (ACID properties), and concurrency control. [cite: 128, 129, 130, 131, 132, 133]
* **Ethics:** Compliance with privacy regulations (e.g., GDPR), data minimization, transparency, consent, data accuracy, user control, bias detection, and data retention policies. [cite: 134, 135, 136, 137, 138, 139, 140, 141]

## Limitations

* The database design is limited to six entities, which is a simplification for a real-world hospital database. [cite: 22, 23, 24] A production system would likely require a more complex schema with additional entities. [cite: 22, 23, 24]

## Conclusion

This project provides a functional database design and implementation for a small private hospital, demonstrating essential database principles and best practices. [cite: 149, 150, 151, 152, 153]

## Author

* Alpha Osman Bah [cite: 1]

## Acknowledgements

* Mr Julius Odede (Lecturer) [cite: 1]

## References

* See the project report for a full list of references. [cite: 154, 155]
