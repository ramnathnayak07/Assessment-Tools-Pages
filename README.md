# Assessment-Tools-Pages

Assessment-Tools-Pages is an online examination system integrated with video surveillance to ensure a secure and fair testing environment. This project allows administrators to create exams, students to take exams, and results to be calculated and displayed. The video surveillance feature captures and monitors the exam sessions to prevent cheating.

Features:
User Authentication: Secure login and registration for users.
Exam Creation: Admins can create, edit, and delete exams.
Question Management: Add, update, and remove questions for each exam.
Video Surveillance: Capture and monitor exam sessions to prevent cheating.
Automated Grading: Automatically grade exams and calculate results.
Result Management: View, download, and analyze exam results.

Installation:
To install and run the Oexamination project locally, follow these steps:

Clone the repository:
git clone https://github.com/ramnathnayak07/Assessment-Tools-Pages.git
cd oexamination

Install dependencies:
npm install

Set up the environment variables:
Create a .env file in the root directory and configure the following environment variables:
DATABASE_URL=your-database-url
JWT_SECRET=your-secret-key

Run the application:
npm start
The application should now be running on http://localhost:3000.

Environment Variables
This project requires the following environment variables:

DATABASE_URL: The connection string for your database.
JWT_SECRET: The secret key used for JWT authentication.
Usage
Admin Operations:

Login as an admin to create and manage exams.
Add questions to the exam.
Monitor the ongoing exams through the video surveillance feature.
Student Operations:

Register and log in as a student.
Enroll in available exams.
Take exams and submit answers.
View your results after the exams are graded.
Surveillance Monitoring:

Admins can review video surveillance footage for any flagged behavior during exams.
API Documentation
For detailed API documentation, including endpoints, request formats, and responses, refer to the Thunder Client collection available in the project. You can import this collection to explore and test the API.

Download Thunder Client Collection (Replace with actual link)
