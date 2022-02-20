# Ecommerce Backend Project

## Description

This project is a SQL-based ecommerce database that may be used to make RESTful API CRUD requests to a server. These requests can be used to create detailed products, tags that help describe the products, and create and manage categories to which products may be associated. This is a versatile database, and may be integrated into a front-end application for dynamic database accessibility.

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [Features](#features)
* [Contribution](#contribution)

## Installation

Clone this project's repository, navigate to the project directory, then run 'npm install' from the command line. Log in to your mySQL shell from the root directory of the project and run ```SOURCE db/schema.sql``` to create the database on your machine. Next, create a .env file containing the code below, filled in with your mySQL login credentials.

```
DB_NAME='ecommerce_db'
DB_USER=''
DB_PW=''
```

From the command line, run ```npm run seed``` to seed the database with sample data, if you so choose.

After you create your .env file, create the database, and optionally seed the database, this project is fully installed.

## Usage

To run the program, ensure your command line is accessing the root directory, and run ```npm run start```. Routes can be tested either in the browser (limited to only GET requests), or with inserted JSON data from insomnia (for all CRUD API requests), using this URL: http://localhost:3001

## Link to Walkthrough Video

[eCommerce Walkthrough](https://drive.google.com/file/d/1jtMKaEnDK5qy7JZxMICoS3exRUP3qYS0/view)

## Credits

Elijah Kanellakis

## GitHub Repository Link

[GitHub Link](https://github.com/kanellakise/ecommerce-backend-elk-wk13)

## Features

This project is built with JavaScript, Node, MySQL, and the Express.js, Sequelize, and dotenv npm packages. The nodemon npm package was used for development.

## Contribution

Fork this project's repository and work to your heart's content! You may make a pull request when you feel sufficient progress has been made, and I will review the changes. Thank you!
