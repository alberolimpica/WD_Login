# WD_Login
This is one of the projects of Angela Yu's 201 Web Development Bootcamp.

This is a webpage that has been developed to work with node.js, express, EJS and Mongo DB.

The aim of this application is to develop a login, log out and suscribe page going through all kinds of level of security:
* Level 1: When an user creates an account we store the email and password in our DB. User can login successfully, the problem is that we store the data as plain text.
* Level 2: We add encryption to our DB by using mongoose encryption on our password. We also use dotenv to store sensitive data. 
