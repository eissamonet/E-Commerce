# E-Commerce


## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)



## Description
E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to the prevalence of these platforms, developers should understand the fundamental architecture of e-commerce sites.

A back-end for an e-commerce site is built using Sequelize to interact with a MySQL database.


## User Story

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies


## Acceptance Criteria
GIVEN a functional Express.js API
- WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
- THEN I am able to connect to a database using Sequelize
- WHEN I enter schema and seed commands
- THEN a development database is created and is seeded with test data
- WHEN I enter the command to invoke the application
- THEN my server is started and the Sequelize models are synced to the MySQL database
- WHEN I open API GET routes in Insomnia for categories, products, or tags
- THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia
- THEN I am able to successfully create, update, and delete data in my database


## Installation

- [MySQL2 package](https://www.npmjs.com/package/mysql2) to connect to your MySQL database and perform queries.
- [Sequelize](https://www.npmjs.com/package/sequelize)
- [Dotenv](https://www.npmjs.com/package/dotenv)


## Usage

Run `npm run seed` to seed data to your database so that you can test your routes. Users are then able to view, add, edit, and delete: Categories, Products, and Tags in Insomnia.

<img width="1362" alt="Screenshot 2023-09-05 at 9 13 46 PM" src="https://github.com/eissamonet/E-Commerce/assets/133728858/62fbbeb1-56f9-40c3-8683-d42c1c154f9f">


<img width="1363" alt="Screenshot 2023-09-05 at 9 12 36 PM" src="https://github.com/eissamonet/E-Commerce/assets/133728858/97bfa9f1-a197-4c1b-bf82-ef6f1817f1e1">



