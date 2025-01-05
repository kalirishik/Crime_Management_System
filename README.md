# Crime Management System

## Objective
This project aims to maintain a record of all the cyber-crime complaints reported by victims and provide a platform for the cyber-crime bureau/police department to offer necessary solutions and assistance to these problems.

## Description
This project is a **console-based Java application** that interacts with a **MySQL database** using **JDBC** for seamless communication. It allows police departments to manage crime records, track criminal activities, and provide insights into case statuses.

---

## Application Snapshots
### Main Class Console
The main console interface provides an interactive way for users to navigate the functionalities, register cases, and retrieve information.

---

## Database Entities
The system includes the following key database entities:

- **Crime**: Stores details of crimes reported.
- **Criminal**: Maintains records of individuals involved in crimes.
- **Victim**: Stores information about victims who reported crimes.
- **Police Station**: Represents police stations managing the crimes.
- **Criminals of Crime**: Links criminals to the crimes they are associated with (foreign key).
- **Victim of Crime**: Links victims to the crimes they reported (foreign key).

### ER Diagram
The Entity-Relationship (ER) Diagram illustrates the relationships between the database entities, ensuring a well-structured design.

---

## Technology Stack
- **Programming Language**: Java
- **Database**: MySQL
- **Driver**: JDBC (Java Database Connectivity)

---

## Features
The Crime Management System provides the following functionalities:

1. **Register Crime**: Add details of new crimes reported.
2. **Register Criminal**: Record information about individuals involved in criminal activities.
3. **Show Status of Case**: Retrieve the current status of any case.
4. **Change Status of Case**: Update the status of a case (e.g., from unsolved to solved).
5. **Search Case in Records**: Look up details of a specific case.
6. **Search Criminal in Records**: Find details of a specific criminal.
7. **Generate Report on Status of Cases**: Get statistics on solved and unsolved crimes.

### Additional Features for Police Stations
- Add and update case files.
- Manage criminal records efficiently.
- Provide statistics on crimes in a particular area, helping with strategic decisions.

---

## Skills Demonstrated
This project demonstrates the following skills:
- Proficiency in Java programming.
- Working knowledge of JDBC for database interaction.
- Database design and management using MySQL.
- Problem-solving and logical thinking for implementing real-world functionalities.

---

## Functional Overview
This system provides a simple console-based interface for:
- Maintaining a record of all crimes in a specific location.
- Tracking solved and unsolved crimes.
- Offering insights and statistics to improve policing efforts in specific areas.

---

## Thank You
Thank you for visiting this project. We hope this system is a valuable tool for effectively managing crime-related data.

