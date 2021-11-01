# WD_Login
This is one of the projects of Angela Yu's 201 Web Development Bootcamp.

This is a webpage that has been developed to work with node.js, express, EJS and Mongo DB.

The aim of this application is to develop a login, log out and suscribe page going through all kinds of level of security:
* Level 1: When an user creates an account we store the email and password in our DB. User can login successfully, the problem is that we store the data as plain text.
* Level 2: We add encryption to our DB by using mongoose encryption on our password. We also use dotenv to store sensitive data. 
* Level 3: If someone takes the time and hacks onto our DB he/she will be able to, eventually, find out our key, thus, being able to see our password. We add a level of security by hashing our data using md5.
* Level 4: With the available resources a hacker can get a hash table that can check the most common used passwords, and check them against our db. With enought time he/she will be able to get other passwords. We will use salting and hashing method of encryption, adding salting rounds to make our password even safer than before. We will use bcrypt.
* Level 5: Using cookies to stablish and maintain a session.
