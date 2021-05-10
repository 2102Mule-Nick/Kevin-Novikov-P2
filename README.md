# American Flights Kevin Novikov

## Project Description
American Flights is a mock program that has CRUD functionality for make-believe flight data. Flight information can be viewed, created, replaced, and deleted. This program was connected to a database and the CRUD functionality has been created exactly to interact with the database.
## Technologies Used
* Mulesoft Runtime 4.3
* Anypoint Studio 7.8
* Anypoint Platform
* Maven 3.8
* PostgreSQL 11
## Features 
* Create Flights
* Get all Flights
* Get Flight by ID

To do:
* Update Flights
* Replace Flights
* Delete Flights
## Getting Started
1) Create desired folder, right click, and select git bash here. Type "git init" in the git console
2) Enter "git remote add origin https://github.com/2102Mule-Nick/Kevin-Novikov-P2.git"
3) Enter "git pull"

You should now be able to load this project from the folder you pulled it to, into your anypoint studio.

Database Commands:

Run this into the database administration tool of your choice: "create new table flights(id serializable, price numeric(7,2), empty_seats numeric, code varchar(10), origin varchar(3), destination varchar(3), depart_date date, plane_type varchar(15), total_seats numeric);"

You will need to connect your database from within the project. 
## Usage
Run the project and open the console from Anypoint Studio. You should now be able to send requests from the console.
