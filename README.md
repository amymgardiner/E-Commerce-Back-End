# E-Commerce Back End

## About

This was a challenge assignment to to build the back end for an e-commerce site. I toke a working Express.js API and configured it to use Sequelize to interact with a MySQL database.

I was given starter code for this challenge. To start, I used the schema.sql file in the db folder to create my database using MySQL shell commands, and seeded the database from the code given to me. I also used environment variables to store my MySQL username, password, and database name.

I then defined the database models based on the requirements for the four models. I also executed association methods on my Sequelize models to create the required relationships between them.

Then I filled out the the unfinished API routes to perform RESTful CRUD operations using my Sequelize models.

Finally, I created the code needed to sync the Sequelize models to the MySQL database on server start.

## How it works

Given a functional Express.js API, when you add your database name, MySQL username, and MySQL password to an environment variable file, then you will be able to connect to a database using Sequelize.

Next, you'll need to enter the schema and seed commands, and then a development database is created and is seeded with the test data.

When you enter the command to invoke the application, then your server is started and the Sequelize models are synced to the MySQL database.

When you open API GET routes in Insomnia for categories, products, or tags, then the data for each of these routes is displayed in a formatted JSON.

Also, when you test API POST, PUT, and DELETE routes in Insomnia, then you will be able to successfully create, update, and delete data in my database.

## How to use
