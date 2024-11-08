## Welcome To The User Management System
##Requirement:
The user management system allows administrators to manage resources and organize user according to their needs and roles while maintaining the security.

## Solution Design :
The user management system using the MVC architecture:
- M(model): Model is mainly the MySQL database where we store the data in user table of this management system using mysql.
- V(view): View is mainly focus the frontend part of the management system using Jsp which is consist html in it's code.
- C(controller): Controller is mainly focus the backend part of the management system using Servlet, which is mainly consist of 3 packages i.e Controller,Dao and Dto packages.
- Here we design the below pages:
- Home page.
- Register page. 
- Login page.
- Add user page.  
- Delete user page. 
- Update user page.

## Technology involved:
- Servlet
- Jsp
- mysql

## Assumption:
- In the user management system we one user can register using registration page.
- We can verify one user using login page.
- We can add a user using add user form.
- A user can update its information using update_user from.
- We can delete our account using delete user page.
