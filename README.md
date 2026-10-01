# School Web Portal

A Java web application for managing student attendance, results, notices and holiday updates.

## Technologies
- Java
- JSP
- Servlets
- JDBC
- MySQL
- HTML
- CSS
- JavaScript
- Apache Tomcat

## Features
- Student/teacher login
- Role-based dashboard
- Student attendance view
- Student result view
- Notices and holiday information
- MySQL database integration through JDBC

## Database setup
1. Install MySQL.
2. Open `database/school_portal.sql`.
3. Run the SQL script.
4. Update the database username/password in `src/main/java/com/priyansh/school/util/DBConnection.java`.
5. Deploy the WAR/project on Apache Tomcat 9.

## Important
Do not commit real database passwords, API keys or other secrets to GitHub.
