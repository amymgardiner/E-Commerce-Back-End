# E-Commerce Back End

## About

This was a challenge assignment to to build the back end for an e-commerce site. I toke a working Express.js API and configured it to use Sequelize to interact with a MySQL database.

I was given starter code for this challenge and added the .env file, defined the models, and created most of the api routes.

## How it works

Given a functional Express.js API, when you add your database name, MySQL username, and MySQL password to an environment variable file, then you will be able to connect to a database using Sequelize.

Next, you'll need to enter the schema and seed commands, and then a development database is created and is seeded with the test data.

When you enter the command to invoke the application, then your server is started and the Sequelize models are synced to the MySQL database.

When you open API GET routes in Insomnia for categories, products, or tags, then the data for each of these routes is displayed in a formatted JSON.

Also, when you test API POST, PUT, and DELETE routes in Insomnia, then you will be able to successfully create, update, and delete data in my database.

## How to use
