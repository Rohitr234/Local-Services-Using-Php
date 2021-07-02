# Homeservices Booking

## Abstract

Created with PHP(Without any Frameworks). You basically register
service providers and then can manage bookings or those providers through admin
login.


## Information

#### What is used?
- PHP7, MySQL
- HTML, Bootstrap(Theme is from [Bootswatch](https://bootswatch.com)), Jquery

#### Login Info
- Admin:
  - Mobile No.: 7070808080
  - Password  : admin123
- Providers:
    - No Providers are registered by default use register screen to create
      some.

#### NOTE
This project is not meant to be used in production. If you want to use it in
real scenario either go over code to remove any security flaws like I stored
passwords in plain text which is not recommended. Although PDO drivers with
parameterised query is used there is no guarntee of full hackerproof safety.


## Features
- Search for professionals for plumbing, mobile repaires, etc. in your city.
- Register as service provider. Update providers information and password
  through.
  Providers Login.
- Admin can see and manage bookings.
- Admin can see and manage providers.

## How To Run The Project?
To run this project, you must have installed a virtual server i.e XAMPP on your PC (for Windows). This Home Service System is in PHP with source code is free to download, Use for educational purposes only!

After Starting Apache and MySQL in XAMPP, follow the following steps.

- 1st Step: Extract file
- 2nd Step: Copy the main project folder
- 3rd Step: Paste in xampp/htdocs/

- 4th Step: Open a browser and go to URL “http://localhost/phpmyadmin/”
- 5th Step: Then, click on the databases tab
- 6th Step: Create a database naming “services” and then click on the import tab
- 7th Step: Click on browse file and select “main.sql” file which is inside the “homeserivces” folder
- 8th Step: Click on go.

### After Creating Database,

- 9th Step: Open a browser and go to URL “http://localhost/homeservices/”




