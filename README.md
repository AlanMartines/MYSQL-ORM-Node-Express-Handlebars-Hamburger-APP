# MYSQL-ORM-Node-Express-Handlebars-Hamburger-APP
> ### Example of using MYSQL with an ORM on an Expressjs server using Nodejs with the MVC model. This application performes all CRUD operations to a MYSQL database. 

## Project Overview

This app allows you to add, edit update and delete hamburgers of your choice with out gaining any of the calories. YUM!

# View Demo  

To view demo click on this link: ([Heroku Demo Link](https://whispering-mesa-65164.herokuapp.com/))

# Getting Started Locally 

To get the Node server running locally:

- Clone this repo ([GIT](https://github.com/dointhedev/MYSQL-ORM-Node-Express-Handlebars-Hamburger-APP.git))
- Install Nodejs on your Mac ([Download](https://www.dyclassroom.com/howto-mac/how-to-install-nodejs-and-npm-on-mac-using-homebrew))
- `npm install` to install all required dependencies
- load the .sql file locally and make sure the credentials match up. 
- `node server.js` to start the node application.


# Code Overview

## Dependencies
- [body-parser](https://www.npmjs.com/package/body-parser) - Parse incoming request bodies in a middleware before your handlers, available under the req.body property.
- [express](https://www.npmjs.com/package/express) - Fast, unopinionated, minimalist web framework (for servers) for node.
- [path](https://www.npmjs.com/package/path) - This is an exact copy of the NodeJS ’path’ module published to the NPM registry.
- [dotenv](https://www.npmjs.com/package/dotenv) - Loads environment variables from .env file
- [handlebars](https://www.npmjs.com/package/handlebars) - andlebars provides the power necessary to let you build semantic templates effectively with no frustration
- [mysql](https://www.npmjs.com/package/mysql) - A node.js driver for mysql. It is written in JavaScript

## Dev Dependencies

- [nodmon](https://www.npmjs.com/package/nodemon) - nodemon will watch the files in the directory in which nodemon was started, and if any files change, nodemon will automatically restart your node application.

## Application MVC Structure

- `server.js` - The entry point to our application for the customer user type.
- `routes.js` - Entry point for the applications routes.
- `/views` - Applications template files using handlebars.
- `/routes` - The routes of this application.
- `/public` - All public facing assets are in this directory.
- `/models` - The application models for use with ORM.
- `/db` - Starter database files.
- `/controllers` - Most of the application's logic for requests and responses are done in this directory. 
- `/config` - Database configuration. 








