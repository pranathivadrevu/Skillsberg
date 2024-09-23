**SkillsBerg ELMS (Educational Learning Management System)**

**Project Overview**

SkillsBerg ELMS is a comprehensive educational learning management system designed to facilitate language learning through a structured, immersive, and user-friendly platform. The system enables users to enroll in courses, manage course content, take quizzes and assignments, and interact with instructors. It supports multiple user roles, including students, instructors, and administrators, while ensuring secure and reliable operations.

**Table of Contents**

Project Overview

Features

Architecture

Installation

Usage

Technologies Used

Contributors

**Features**
**User Registration & Login:** Secure user registration and login system for students, instructors, and administrators.

**Course Enrollment:** Students can browse and enroll in language courses.

**Course Management:** Instructors can manage course content, assignments, and quizzes.

**Quiz and Assignment Management:** Support for creating, submitting, and grading quizzes and assignments.

**User Roles and Access Control:** Role-based access control to ensure users access only relevant features based on their roles.

**Progress Tracking:** Allows students to track their course progress, assignment submissions, and quiz scores.

**Support System**: Includes a user support interface for assistance with technical or course-related issues.

**Architecture**
The SkillsBerg ELMS is built on a modular architecture, following principles like Single Responsibility and Open/Closed. The system is designed to scale easily, providing a reliable and adaptable platform for language learning.

**Frontend**: Built using React.js for flexibility and dynamic user interaction.

**Backend:** Powered by Node.js for scalability, handling user management, course management, and other server-side operations.

**Database:** Firebase (NoSQL) is used for real-time data management and easy backend integration.

**Authentication:** User authentication and authorization are handled securely using role-based access control mechanisms.



**Installation**
To run this project locally, follow these steps:

**Clone the repository:**

bash
Copy code
git clone https://github.com/your-repo/skillsberg-elms.git
cd skillsberg-elms
Install dependencies:

bash
Copy code
npm install
Set up Firebase:

**Create a Firebase project.**
Set up Firebase Firestore and Authentication.
Configure Firebase credentials in the project.
Start the development server:

bash
Copy code
npm start
**Access the app in your browser at http://localhost:3000.**

**Usage**
**For Students:**

Register and log in to browse available courses.
Enroll in a course, access materials, and submit assignments.
Track progress, view deadlines, and communicate with instructors.
For Instructors:

Manage course content, quizzes, and assignments.
Track students' progress and provide feedback.
For Administrators:

Manage users, handle course catalogs, and maintain overall system security and performance.
Technologies Used
Frontend: React.js
Backend: Node.js
Database: Firebase Firestore (NoSQL)
Authentication: Firebase Authentication
Deployment: Google Cloud Platform (GCP)

**Contributors**

**This project was developed by:**

Bhanu Teja Panguluri

Pranathi Vadrevu

Revanth Maturu

Sudhanshu Dubey

Tarang Nair
