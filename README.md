# Foundation of Computer Science Assignment

**Student Name:** Archit Aryal
**Student ID:** 250222
**Course:** BSc (Hons) Ethical Hacking and Cybersecurity
**Module:** ST4015CMD – Foundation of Computer Science

---

# Overview

This repository contains the supporting materials, scripts, diagrams, and documentation for the Foundation of Computer Science assignment.

The assignment is divided into three major tasks:

* Task 1 – Secure Data Exchange with Encoding Formats
* Task 2 – Classroom Seating Arrangement Problem (P vs NP)
* Task 3 – College Club Membership Database Normalization

---

# Task 1 – Encoding Formats and Secure Data Exchange

This task explores how encoding formats such as Base64, ASCII, Hex, and URL encoding support secure and reliable data exchange across modern web protocols.

The report discusses how these encoding formats interact with protocols such as:

* HTTPS
* TLS
* SMTP
* REST APIs
* OAuth authentication systems

The task also evaluates security risks such as encoding-based obfuscation used by attackers and proposes improved encoding strategies.

Supporting materials for this task include explanatory documentation and diagrams demonstrating how encoded data flows through secure protocols.

Folder: `Task1-Encoding`

---

# Task 2 – Classroom Seating Arrangement Problem

This task investigates the computational complexity of arranging students in a classroom while satisfying two constraints:

1. Friends must not sit next to each other.
2. Students from the same city must not sit next to each other.

The problem is used to explain the concepts of:

* P problems
* NP problems
* Brute force search
* Heuristic problem-solving strategies

The report analyzes why verifying a seating arrangement is easy while finding a valid arrangement becomes difficult as the number of students increases.

The repository includes supporting explanations for the brute force and heuristic approaches.

Folder: `Task2-Seating-Problem`

---

# Task 3 – College Club Membership Management System

This task focuses on database normalization and relational database design.

The original dataset contained multiple issues including:

* Data redundancy
* Update anomalies
* Insertion anomalies
* Deletion anomalies

The database was normalized into:

* Student table
* Club table
* Membership table

The repository includes SQL scripts that define the database schema, insert sample data, and perform JOIN queries to retrieve combined information.

Folder: `Task3-Database`

---

# How to Use the SQL Files

The SQL scripts can be executed using any relational database system such as:

* MySQL
* PostgreSQL
* SQLite
* SQL Server

---

# Repository Contents

| Folder                | Description                                                            |
| --------------------- | ---------------------------------------------------------------------- |
| Task1-Encoding        | Explanation of encoding formats used in secure data transmission       |
| Task2-Seating-Problem | Analysis of the seating arrangement problem and algorithmic approaches |
| Task3-Database        | SQL scripts for database design and queries                            |

---

# Conclusion

This repository demonstrates how theoretical computer science concepts and practical database design can be applied to real-world computing systems. The tasks highlight the importance of secure communication protocols, algorithmic reasoning, and efficient data management in modern computing environments.

