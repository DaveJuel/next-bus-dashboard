# README #

This file is to instruct you installing and successfully running Next Bus Dashboard.

### What is this repository for? ###

* Next Bus Dashboard is a next bus app dashboard, to help agency and traffic police manage public transportation.
* Version 1.0.0 Unreleased

### INSTALLATION PREREQUISITES ###

* Apache2 installed
* PHP 5.7 and greater installed
* Mysql

### CONFIGURATION DETAILS ###
After cloning this project to your desired directory[Windows: C:~/xampp/htdocs , Linux: /var/www/html], you need to do the following.  
  
* Configure the database  
-> In DB management app (eg:phpmyadmin, workbench,...), create a database.   
-> Import the database(next-bus.sql) from next-bus-dashboard root folder, to your newly created database.  
-> Go into ~/next-bus-dashboard/admin/includes and open file 'config.php' change your local connection values respective to your settings.
-> Change to database connection respective to your mysql configurations on line 9.  

* Run the application  
After finishing the steps above, you will need to run the app on your local machine.  
-> Go into your browser and type _localhost/next-bus-dashboard_.  
-> If all was done successfully, you will find a login page.   
 The dashboard accepts 3 usertypes, below is their username, password and role respectively
 1) username: traffic
    password: test
    role: View journey and set status to closed or opened to inform agencies
 2) username: agency
    password: test
    role: Add drivers, assign driver to route and view journey info
 3) username: administrator
    password: test
    role: Sets up the system, and manages the landing page. 

NOTE: To avoid hardship during installation, you may visit the system on this link: https://next-bus-dashboard.herokuapp.com               
  
There you go, every thing done well.  
### Contribution guidelines ###  
  
* Writing tests  
* Code review  
* Other guidelines  
* Investment  
  
### Who do I talk to? ###  
In case you need help!  
  
* David NIWEWE[phone:+250788353869 , email:davejuelz@gmail.com ]
