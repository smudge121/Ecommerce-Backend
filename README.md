# Ecommerce-Backend

## Description

This project is a simple Backend application to handle detailed databases for various purposes such as ecommerce.  The applications stores products, categories, and tags that can be added, edited, viewed, and deleted.

## Usage

Download the code from the repository and install the necessary packages to the application.  The user must also create a database to house this information.  The user must provide a username, password, and database name in a dotenv file to connect to mysql.  

An example video is provided at this link:
https://drive.google.com/file/d/1L3TxDr0PsQKru2M1TN9GkIpMCI4BnGsV/view 

## Installation

After downloading, the user can run the command 

    node seeds/index.js

to seed the database with dummy values for testing purposes.

The command

    npm start

will start up the server allowing the user to use an application like Insomniac to query their database.

## Credits

1. Developed by Jaret Ishii
2. Packages used: 

    express,
    mysql2,
    dotenv,

