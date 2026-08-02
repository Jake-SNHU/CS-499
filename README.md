# CS 499 Computer Science ePortfolio

# Overview

This repository contains the enhancement artifacts, documentation, and supporting materials created for my **CS 499 Computer Science Capstone** at **Southern New Hampshire University**.

The goal of this repository is to demonstrate my growth as a software developer by enhancing previously completed coursework in three major areas of computer science:

- Software Design and Engineering
- Algorithms and Data Structures
- Databases

Rather than creating entirely new applications, each artifact was selected from previous coursework and significantly improved to demonstrate stronger software engineering practices, more efficient algorithms, and secure database implementation.

---

# Featured Artifacts

## 1. Android Event Tracking Application (CS 360)

Originally developed during **CS 360: Mobile Architecture and Programming**, this Android application allows users to:

- Create user accounts
- Authenticate users
- Store events in SQLite
- Display events using RecyclerView
- Delete events
- Search events
- Sort events
- Edit existing events
- Request SMS permissions for reminders

This application was enhanced during the CS 499 Capstone to improve software quality, efficiency, and security.

---

## 2. Grazioso Salvare Animal Dashboard (CS 340)

Originally developed during **CS 340: Client/Server Development**, this project uses:

- Python
- MongoDB
- Dash
- Plotly
- Dash Leaflet

The dashboard allows users to:

- Query MongoDB
- Filter rescue animals
- Display interactive charts
- Display animal locations on a live map

The CRUD module and dashboard were enhanced during CS 499 to improve security, database efficiency, maintainability, and usability.

---

# Enhancement Summary

## Software Design & Engineering (Enhancement One)

### Improvements

- Refactored large methods into reusable helper functions
- Added detailed method documentation
- Added input validation throughout the application
- Added exception handling
- Improved class organization
- Improved readability and maintainability
- Reduced duplicated code
- Improved user feedback through Toast messages
- Improved RecyclerView update process

### Primary Files where enhancements were made

### Android Project

- `DashboardActivity.java`
- `LoginActivity.java`
- `DatabaseHelper.java`
- `EventAdapter.java`
- `PermissionActivity.java`

---

## Algorithms & Data Structures (Enhancement Two)

### Improvements

- Implemented Binary Search for locating events
- Added event searching functionality
- Added dynamic event sorting
- Implemented alphabetical, date, and time sorting
- Improved RecyclerView efficiency using cursor swapping
- Reduced unnecessary Activity recreation
- Optimized SQLite queries for faster retrieval
- Added event update functionality for editing existing events
- Added SHA-256 password hashing for secure user authentication
- Improved database validation and input checking
- Replaced raw SQL queries with parameterized SQLite queries
- Added reusable helper methods for searching, updating, and sorting events
- Improved overall data management and application performance

### Primary Files where enhancements were made

- `DashboardActivity.java`
- `DatabaseHelper.java`
- `EventAdapter.java`
- `EventSearch.java`
- `activity_dashboard.xml`

---

## Databases (Enhancement Three)

### MongoDB Dashboard Improvements

- Refactored the MongoDB CRUD module into reusable methods
- Added connection validation and centralized exception handling
- Added projection support for more efficient queries
- Added sorting support for MongoDB searches
- Added pagination support for large datasets
- Improved CRUD method validation and error reporting
- Added dashboard search functionality
- Added dashboard sorting controls
- Added dashboard statistics and summary metrics
- Improved interactive filtering of rescue animals
- Enhanced Plotly visualizations
- Improved Dash layout organization and code readability
- Optimized MongoDB queries to reduce unnecessary database operations

### Primary Files where enhancements were made

- `CRUD_Python_Module.py`
- `ProjectTwoDashboard.ipynb`

# Repository Structure
- CS360_Project3_Original (contains the original complete android app)
- CS360_Project3_Enhancement1 (contains the complete android app after all category one enhancements)
- CS360_Project3_Enhancement2 (contains the complete android app after all category two enhancements)
- CS340_Project_Original (contains the original MongoDB dashboard project files)
- CS340_Project_Enhancement3 (contains the enhanced MongoDB dashboard project files)

---

# Technologies Used

## Mobile Development

- Java
- Android Studio
- SQLite
- RecyclerView
- XML

## Database Development

- MongoDB
- PyMongo
- Jupyter Notebook

## Dashboard Development

- Dash
- Plotly Express
- Dash Leaflet
- Pandas

## Development Tools

- Git
- GitHub
- IntelliJ / Android Studio
- VS Code

---

# Skills Demonstrated

This repository demonstrates experience with:

### Software Engineering

- Object-Oriented Programming
- Code Refactoring
- Modular Design
- Exception Handling
- Documentation
- Maintainability

### Algorithms & Data Structures

- Binary Search
- Sorting Algorithms
- Efficient Data Retrieval
- RecyclerView Optimization
- Cursor Management

### Database Development

- SQLite
- MongoDB
- CRUD Operations
- Query Optimization
- Secure Password Storage
- SHA-256 Hashing
- Data Validation

### Security

- Input Validation
- Password Encryption
- Parameterized Queries
- Error Handling
- Secure Authentication

---

# Course Outcomes Demonstrated

This repository demonstrates the CS 499 course outcomes by showing the ability to:

- Design and evaluate secure, maintainable software solutions.
- Apply algorithmic and data structure concepts to improve software performance.
- Design, implement, and optimize relational and NoSQL database systems.
- Refactor and enhance existing software using professional software engineering practices.
- Communicate technical decisions through professional documentation, code reviews, and narratives.

---

# Supporting Documentation

This repository also includes the documentation developed throughout the capstone process:

- Code Review
- CS 499 Milestone Two (contains the narrative that describes the enhancements made in Category one)
- CS 499 Milestone Three (contains the narrative that describes the enhancements made in Category two)
- CS 499 Milestone Four (contains the narrative that describes the enhancements made in Category three)


These documents explain the reasoning behind each enhancement and demonstrate the software engineering process used throughout the project.

---

# Repository Status

**Status:** Completed

This repository contains the completed enhancement artifacts submitted for the **CS 499 Computer Science Capstone** at Southern New Hampshire University. Together, these projects demonstrate my ability to analyze existing software, implement meaningful enhancements, improve security and performance, and produce professional documentation suitable for inclusion in a technical ePortfolio.
