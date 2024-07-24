# CampusActivitySystem
My First Enterprise Programming Project: Campus Activity Portal!

**Overview:**
This project is a comprehensive web application designed to streamline campus activities, enhancing the user experience for both students and administrators. The Campus Activity Portal offers functionalities like user registration, login, activity management, and an admin dashboard.

**Technologies Used:**

_Front-End:_
- HTML, XHTML & CSS: Structuring and styling the web pages.
- JSP (JavaServer Pages): Dynamically generating HTML content.

_Back-End:_
- Servlets: Handling server-side processing.
- JDBC (Java Database Connectivity): Database interaction.

_Database:_
- MySQL: Storing and managing user data, activity details, and feedback messages.

_Development Environment:_
- Red Hat JBoss: Application server for deploying the web app.
- CodeReady Studio: IDE for Java EE development.

**Key Features:**

_User Registration & Login:_
- Secure registration and authentication.
- Strong password validation.

_Admin Dashboard:_
- View and manage user activities.
- Display registered activities in a table format.

_User Dashboard:_
- Register for campus activities.
- Submit feedback and view activity history.

_Activity Management:_
- Simple form for activity registration.
- Admins monitor activities and participation.

_Feedback System:_
- Users submit queries and suggestions.
- Admins manage feedback entries.

**Database Schema:**

_User Table:_ Stores user info (username, password, email, phone).

_Activity Table:_ Details about each activity (ID, name, branch, username, phone).

_Contact Table:_ Records feedback messages (name, email, phone, message).

**Project Flow:**

_User Interaction:_ JSP pages for registration, login, and activity management.

_Server Processing:_ Servlets handle requests, process data, and interact with MySQL via JDBC.

_Data Management:_ Ensuring data persistence and integrity.

_Admin Oversight:_ Admins use the dashboard to oversee activities and feedback.
