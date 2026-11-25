\# Student Profile Management System

## CSC584 – Individual Assignment 2

### Student Information

- **Name:** Faiz Nur Iman
- **Student ID:** 2026137397
- **Course:** CSC584
- **Institution:** Universiti Teknologi MARA (UiTM)

## 1. Project Description

The Student Profile Management System is a Java web application developed to allow students to register, store, view and search their personal and academic information.

The system uses Java Servlets to process user requests, JavaBeans to store student information, JSP to display dynamic content and JDBC to connect to the Apache Derby database.

## 2. System Features

- Register a new student profile.
- Save student information into the database.
- Display submitted student information.
- View all registered student profiles.
- Search profiles by Student ID.
- Search profiles by student name.
- Case-insensitive search.
- Reset search results.
- Required field validation.
- Duplicate Student ID prevention.
- Consistent and responsive user interface.

## 3. Technologies Used

| Technology | Purpose |
|---|---|
| HTML | Student registration form |
| CSS | User interface design |
| Java Servlet | Request processing |
| JavaBean | Student data representation |
| JSP | Dynamic web pages |
| JSTL | Display and process JSP content |
| JDBC | Database connectivity |
| Apache Derby | Database management |
| GlassFish 4.1.1 | Application server |
| NetBeans | Development environment |

## 4. Database Information

- Database name: StudentProfilesDB
- Database system: Apache Derby
- Schema: APP
- Table name: PROFILE

The PROFILE table contains the following fields:

- STUDENTID (Primary Key)
- NAME
- PROGRAMME
- EMAIL
- HOBBIES
- INTRODUCTION

The database.sql file contains the SQL statements required to create the table and insert sample records.

## 5. Installation and Setup

1. Download or clone this GitHub repository.
2. Open the project using NetBeans.
3. Configure a compatible Java Development Kit and GlassFish Server 4.1.1.
4. Start the Apache Derby database server.
5. Create a database named StudentProfilesDB.
6. Execute the database.sql file in the newly created database.
7. Configure the database connection settings in DBConnection.java.
8. Ensure the Derby JDBC driver and JSTL libraries are available.
9. Clean and Build the project.
10. Run the application using GlassFish.

## 6. System URL

Default local application URL:

http://localhost:8080/ProfileManagementSystem/

The URL may differ depending on the GlassFish configuration.

## 7. System Screenshots

### Student Registration

![Student Registration](screenshots/01_registration.png)

### Successful Registration

![Successful Registration](screenshots/02_profile_saved.png)

### View All Student Profiles

![All Student Profiles](screenshots/03_all_profiles.png)

### Search by Student ID

![Search by Student ID](screenshots/04_search_id.png)

### Search by Name

![Search by Name](screenshots/05_search_name.png)

### No Matching Results

![No Matching Results](screenshots/06_no_results.png)

### Database Records

![Database Records](screenshots/07_database.png)


