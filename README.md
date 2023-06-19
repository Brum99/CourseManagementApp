# CourseManagementApp
Mock University course enrollment system using JavaFX with integrated SQLite database 
Course Management System (CMS) Readme
Overview
The Course Management System (CMS) is a Java-based application built with JavaFX, SQLite, and FXML. It provides a simple and user-friendly interface for managing courses. Users can create a profile, enroll in courses, view a timetable, withdraw from courses, and export a file of enrolled courses. This readme document provides an overview of the CMS, installation instructions, and usage guidelines.

System Requirements
To run the CMS, ensure your system meets the following requirements:

Java Development Kit (JDK) 8 or higher
JavaFX library
SQLite database
Java IDE (e.g., Eclipse, IntelliJ IDEA) or any text editor
Web browser (for viewing the timetable and exporting files)
Installation
To install and set up the CMS, follow these steps:

Clone the Repository:

Clone the CMS repository to your local machine using Git or download the source code as a ZIP file.
Import Project:

Open your preferred Java IDE (e.g., Eclipse, IntelliJ IDEA).
Import the CMS project from the cloned repository or extracted ZIP file.
Configure Libraries:

Configure the JavaFX library in your IDE to ensure it is recognized and accessible within the project.
Refer to your IDE's documentation or online resources for specific instructions on configuring JavaFX.
Database Setup:

Ensure you have SQLite installed on your system.
Create a new SQLite database file (e.g., cms.db).
Execute the provided SQL scripts or use an SQLite client to create the necessary tables and schema for the CMS.
Configure Database Connection:

Open the CMS source code in your IDE.
Locate the database connection configuration file (e.g., DBConfig.java).
Update the configuration settings with the appropriate database file path, credentials, and other relevant details.
Build and Run:

Build the CMS project in your IDE to compile the code.
Run the CMS application, and the graphical user interface should open.
Usage
Once the CMS application is up and running, follow these guidelines to use its features:

Create a Profile:

On the CMS interface, navigate to the profile creation section.
Provide your first name, last name, username, and password to create a user profile.
Enroll in Courses:

Browse the available courses listed in the CMS.
Select the desired courses and enroll by following the enrollment instructions.
View Timetable:

Access the timetable section in the CMS.
View the scheduled classes, including course name, date, time, and location.
Withdraw from Courses:

If needed, navigate to the course withdrawal section.
Select the courses you wish to withdraw from and confirm the withdrawal.
Export Enrolled Courses:

In the CMS interface, find the export functionality or option.
Select the desired export format (e.g., CSV, Excel).
Choose a file location and export the enrolled courses.
Note: For detailed instructions on using specific features or navigating through the CMS, consult the CMS documentation or user guide.
