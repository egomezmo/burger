# Burger app

## DB Setup
** schema.sql ** A file that creates dB with table with these fields:

1. id: an auto incrementing int that serves as the primary key.
1. burger_name: a string.
1. devoured: a boolean.

** seeds.sql ** file. In this file are the lines to populate the burgers table with 10 entries.


## Config Setup
** connection.js ** Setup the code to connect Node to MySQL.
** orm.js ** File (Object Relational Mapping) Allows us convert data to storage in the Data Base (dB).

1. selectAll()
1. insertOne()
1. updateOne()
1. deleteOne()


Export the ORM object in module.exports.



Model setup



Inside your burger directory, create a folder named models.


In models, make a burger.js file.
Inside burger.js, import orm.js into burger.js

Also inside burger.js, create the code that will call the ORM functions using burger specific input for the ORM.
Export at the end of the burger.js file.





Controller setup


Inside your burger directory, create a folder named controllers.
In controllers, create the burgers_controller.js file.
Inside the burgers_controller.js file, import the following:



Express
burger.js



Create the router for the app, and export the router at the end of your file.



View setup


Inside your burger directory, create a folder named views.



Create the index.handlebars file inside views directory.

Create the layouts directory inside views directory.


Create the main.handlebars file inside layouts directory.
Setup the main.handlebars file so it's able to be used by Handlebars.
Setup the index.handlebars to have the template that Handlebars can render onto.
Create a button in index.handlebars that will submit the user input into the database.