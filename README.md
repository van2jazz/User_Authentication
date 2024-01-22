# User_Authentication
+ This Repo contains a simple user authentication system using Spring MVC. It incorporates Spring Data JPA for effortless communication with a PostgreSQL database. The system ensures robust authentication through Auth0, providing a secure mechanism for accessing the REST API.

+ The APIs are well-documented and easily accessible through Swagger UI, making it simple for developers to test.

+ It is a secure and robust authentication system built using Java Spring Boot. It provides a seamless user registration process through a RESTful API endpoint (/api/auth/signup). The service ensures data integrity and security by leveraging encryption techniques for sensitive user information.

# Key Features:
+ User Registration: Enables users to register with the system securely.
+   Role-based Access Control: Implements role-based access control with predefined roles such as USER, MODERATOR, and ADMIN.
+   Token-based Authentication: Utilizes JSON Web Tokens (JWT) for secure and stateless authentication.
+  Password Encryption: Safeguards user passwords through the use of BCrypt password hashing.

#  Running the app
1. Clone the repository: git clone https://github.com/van2jazz/ECommerce_Application 
2. Import the project:

+ Click File > Import...
+ Select Maven > Existing Maven Projects and click Next
+ Browse to the project directory and click Finish

3. Update the values in application.properties with your database connection details.
4. Run the app: Right-click the project in the Package Explorer and click Run As > Spring Boot App.

# API documentation
+ API documentation is available via Swagger UI at http://localhost:8080/swagger-ui/index.html (note: app must be running)

#Swagger UI
![test1](https://github.com/van2jazz/User_Authentication/assets/53022905/a0d69338-d5d3-4e86-ae9d-c8ec78415618)
