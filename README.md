# Student Management System

## Project Description
The Student Management System is a web-based application developed using Node.js, Express.js, EJS, and MySQL. It helps users manage student information efficiently.

## Features
- View the list of students
- Add new student records
- Search students by student ID, first name, last name, or course
- Edit student information
- Delete student records
- Validate student information

## Technologies Used
- Node.js
- Express.js
- EJS
- MySQL
- HTML and CSS
- Git and GitHub

## Installation and Setup

1. Clone or download the project repository.
2. Open the project folder in Visual Studio Code.
3. Open the terminal and run:

   `npm install`

4. Create a MySQL database named `student_management`.
5. Configure the database credentials in your local `.env` file.
6. Start the application:

   `node app.js`

7. Open your browser and visit:

   `http://localhost:3000`

## Database
The system uses a MySQL database named `student_management` and a `students` table to store student information.

## Security
- Database queries use parameterized statements.
- Environment variables are used for database configuration.
- The `.env` file and `node_modules/` folder should not be uploaded to GitHub.

## Developers
Developed as a student project.