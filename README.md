# AI-Powered Adaptive E-Learning System for Personalized Student Learning
An AI-powered adaptive e-learning system that personalizes students’ learning experiences based on their quiz performance. Built with PHP, MySQL, HTML, CSS, Bootstrap 5, and JavaScript, it provides course management, online assessments, personalized learning recommendations, progress tracking, analytics, and automatic certificate generation.
#  Project Overview
The AI-Powered Adaptive E-Learning System for Personalized Student Learning was designed and implemented to address the limitations of conventional e-learning platforms that provide the same learning content and progression pathway to all students.
The system monitors students’ academic performance through online assessments and uses predefined AI rules to determine the most appropriate learning action for each student.
Depending on the student’s performance, the system can recommend:
•	Repeating a lesson
•	Reviewing easier learning materials
•	Studying revision materials
•	Attempting additional practice
•	Proceeding to the next lesson
•	Accessing advanced learning materials
# Objectives
The main objective of the project is to design and implement an adaptive e-learning platform capable of providing personalized learning experiences.
The system is designed to:
•	Provide online learning resources.
•	Allow students to register and authenticate.
•	Enable students to enroll in courses.
•	Deliver lessons and learning materials.
•	Conduct online quizzes and assessments.
•	Analyze students’ quiz performance.
•	Generate personalized learning recommendations.
•	Track student learning progress.
•	Provide learning analytics.
•	Allow administrators to manage courses, lessons and quizzes.
•	Generate course completion certificates in PDF format.
# Adaptive Learning Features
The system incorporates a rule-based AI mechanism that evaluates quiz performance and determines an appropriate learning pathway.
# Analytics
The platform provides graphical performance and learning analytics using Chart.js.
# Certificate Generation
Students who successfully complete their learning requirements can generate and download course completion certificates in PDF format.
# Database Setup
The project contains a database directory:
database/database.sql
The SQL file should be imported into MySQL using phpMyAdmin.
Step 1: Start MySQL
Open XAMPP and start:
MySQL
Step 2: Open phpMyAdmin
Open your browser and navigate to:
http://localhost/phpmyadmin/
Step 3: Create/Select the Project Database
Create the database required by the project if it is not created automatically by the SQL script.
Use the database name expected by config.php.
Step 4: Import the SQL File
Inside phpMyAdmin:
1.	Select the project database.
2.	Click Import.
3.	Choose:
database/database.sql
4.	Click Import or Go.
5.	Wait for the import to complete.
The database design documented in the project contains tables for administrators, students/users, courses, lessons, quizzes, questions, results, recommendations, login logs, certificates and progress records.
