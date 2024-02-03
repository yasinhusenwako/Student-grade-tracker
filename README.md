## Student Grade Visualization System Project

Welcome to the Student Grade Visualization System project! This Java-based application provides a comprehensive solution for managing grade-related data, including students, courses, departments, and semester-wise scores.

### Table of Contents
- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Project Structure](#project-structure)
- [Contributors](#contributors)
- [Contact](#contact)

### Description
This project is a JavaFX application that enables users to input and analyze student performance data. It consists of several components, including a registration form for entering student information, a course entry interface for adding course scores, and a chart display for visualizing performance data in a bar chart. The application calculates and displays the mean and median scores of students based on the entered data.

### Features
- **User Authentication and Registration:**
  - Users can log in and register to access the application's features.
- **Student Information Management:**
  - The application allows the entry and storage of student details, including names and IDs.
- **Course Score Entry:**
  - Users can input scores for various courses for each student, used for performance analysis.
- **Statistical Analysis:**
  - The application calculates and displays mean and median scores, providing a comprehensive overview of student performance.
- **Data Visualization:**
  - The main feature is the performance analysis page, displaying a bar chart representing scores of each student in different courses.

### Extended Features
- **Data Validation:**
  - The system includes robust data validation mechanisms for accepting only valid and properly formatted data, minimizing errors, and enhancing data integrity.
- **Multi-User Support:**
  - Supports multiple user accounts, each with its login credentials and access privileges for secure and personalized interactions.
- **Real-time Updates:**
  - Changes made to the database reflect in real-time, ensuring users always have access to the most up-to-date information.
- **Comprehensive Logging:**
  - Maintains a detailed log of user activities for auditing and tracking system usage.
- **Interactive Dashboard:**
  - Provides a centralized view of key metrics and summaries, offering administrators a quick overview of the system's performance.

### Installation
1. **Clone the Repository:**
   - Copy the project to your local machine using Git.

2. **Run the Application:**
   - Import the project into your preferred Java IDE.
   - Run the `LoginApp` class to start the application.

3. **Database Setup:**
   - The application uses SQLite, and the database file is named `student1.db`.
   - Ensure SQLite is installed.
   - Database tables are created automatically on the first run.

### Usage
- **Login:**
  - Upon launching the application, users are presented with a login screen. Default credentials are provided for initial access.

- **Course Entry:**
  - Use the `CourseEntryApp` to add students, input scores, and track academic data.

- **Chart Display:**
  - Explore the `ChartDisplayApp` to visualize academic trends through charts.

### Dependencies
- **Java 8 or Higher:**
  - Ensure a compatible version of Java is installed on your system.
- **JavaFX:**
  - The application relies on JavaFX for creating the graphical user interface and managing user interactions.
- **SQLite JDBC Driver:**
  - Necessary for establishing a connection to the SQLite database.

### Project Structure
- **chart.chartop:**
  - Main package containing Java classes for the application.
- **chartController:**
  - Controller class for the performance analysis page.
- **ChartDisplayApp:**
  - Main class to launch the application.
- **CourseEntryApp:**
  - Class for launching the course entry page.
- **CourseEntryController:**
  - Controller for the course entry page.
- **LoginApp:**
  - Class for launching the login page.
- **logincontroller:**
  - Controller for the login page.
- **RegistrationDataEntry:**
  - Class for launching the registration page.
- **RegistrationDataEntryController:**
  - Controller for the registration page.
- **User:**
  - Class representing a user with a course and score.

### Contributors
- [Sudeis Fedlu](https://github.com/sudeisf)
- [Fira0985](https://github.com/Fira0985)
- [Mercy Wub](https://github.com/mercywub)
- [Hamdi Ab](https://github.com/hamdi-ab)
- [Muaz Redi](https://github.com/muazredi-1425)
- [Yasinhusen Wako](https://github.com/yasinhusenwako)
- [Garoma Makure](https://github.com/GaromaMakure)

### Contact
**Sudeis Fedlu (Project Leader)**
- Email: sudeisfed@gmail.com
