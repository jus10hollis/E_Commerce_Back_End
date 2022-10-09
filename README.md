# E_Commerce_Back_End

## Installation

Run `npm run seed` to seed data to the database so that you can test your routes. Run `npm start` to create an instance of the back end and test GET routes for all categories, all products, and all tags in Insomnia. Then, test GET routes for a single category, a single product, and a single tag. Finally, test POST, PUT, and DELETE routes for categories, products, and tags.

## Description

A back end for an e-commerce site. We have configured a working Express.js API to use Sequelize to interact with a MySQL database. This back end does the following:

- Connects to a MySQL database using the [MySQL2](https://www.npmjs.com/package/mysql) and [Sequelize](https://www.npmjs.com/package/sequelize) packages.

- Stores sensitive data, like a user’s MySQL username, password, and database name, using environment variables through the [dotenv](https://www.npmjs.com/package/dotenv) package.

- Syncs Sequelize models to a MySQL database on the server start.

- Includes column definitions for all four models.

- Includes model associations.
