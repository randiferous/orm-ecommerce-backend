# E-commerce Back End Challenge

The purpose of this assignment was to deepen our understanding of Object-Relational Mapping. This was done by letting us connect various parts of an application's back-end, namely its MySQL Database and API routes, through a Node.js package called Sequelize.

## Description

This is a back-end application for an e-commerce site that allows the company to view information about it's products, their categories, and tags.  It also enables the company to create, update, or delete data whenever it is necessary.

## Installation/Usage

Follow these steps in order to use this application:

1) Clone this repository into a local directory.

2) Open up your command-line application and navigate to the directory holding this repository.

3) Type and enter "npm init -y" to initialize Node.js, and then type and enter "npm install" to download the required dependencies.

4) Create a file called .env, and enter the database, your MySQL username, and your MySQL password in the following format:
 
DB_NAME='ecommerce_db'

DB_USER='"your username"' (make sure to add your actual MySQL username)

DB_PASSWORD='"your password"' (make sure to add your actual MySQL password)

5) Access your MySQL shell (use "mysql -u root -p" in the command-line) and create the schema by typing "source db/schema.sql". After that, make sure you leave the MySQL Shell using "quit".

6) Seed the database from the command-line with "npm run seed".

7) Start the application server with "npm start".

8) Open an API software such as Insomnia to test the routes!

## Reflection

To be honest, this challenge was simpler than most of the other ones.

The most difficult part had to be setting up the files properly.  For instance, making sure that the environment variable was in place and that sequelize was being implemented in the proper files all took a bit of time to ensure.

Otherwise, most of the code, especially creating the models and routes, was pretty straightforward.  I was able to reference the module for most of this part.

## Walkthrough Video

 Here is the link to the walkthrough video of the application: https://drive.google.com/file/d/136CjcvV2lFFKlNB6n1B73YDdzuWg79oy/view?usp=sharing