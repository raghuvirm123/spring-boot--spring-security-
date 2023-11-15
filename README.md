# spring-boot--spring-security-

#Overview
The Spring Boot Security project is a web application that provides a secure authentication and authorization system using Spring Security. It supports two user roles: User and Admin. Users can access general pages, while Admins have additional access to admin-specific pages.

#Features
1. User Authentication and Authorization
The application uses Spring Security to manage user authentication and authorization.
There are two roles: User and Admin.
Users need to log in to access certain pages, and the access level is determined by their assigned role.
2. Login Functionality
Custom login page (/login) is provided for users to enter their credentials.
Authentication is handled securely, and password storage is encrypted.
Users can log in with their assigned roles, granting them specific permissions.
3. Logout Functionality
Users can log out securely using the /logout endpoint.
After logging out, users are redirected to the home page.
4. Admin-specific Pages
Admins have access to pages under the /admin path.
These pages are secured and can only be accessed by users with the Admin role.
