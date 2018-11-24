# Burger app

## DB Setup
**schema.sql** A file that creates dB with table with these fields:

1. id: an auto incrementing int that serves as the primary key.
1. burger_name: a string.
1. devoured: a boolean.

**seeds.sql** file. In this file are the lines to populate the burgers table with 10 entries.


## Config Setup
**connection.js** Setup the code to connect Node to MySQL.
**orm.js** File (Object Relational Mapping) Allows us convert data to storage in the Data Base (dB).

1. selectAll()
1. insertOne()
1. updateOne()
1. deleteOne()

## Model setup
**burger.js** To drive table "burger" of burgers_Db


## Controller setup
**burgers_controller.js** The router for the app.



## View setup
**main.handlebars** Begins the html with generals, headers and calls the body.
**index.handlebars**

