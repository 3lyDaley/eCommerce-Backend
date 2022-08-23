# eCommerce Backend

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)


 ## Contents
 
 - [Description](#description)
    - [User Story](#user-story)
    - [Acceptance Criteria](#acceptance-criteria)
 - [Dependencies](#dependencies)
 - [Installation Instructions](#installing)
 - [Execution](#executing-program)
 - [Demos](#demos)
    - [`Category` Functions](#categories)
    - [`Product` Functions](#products)
    - [`Tag` Functions](#tags)
 - [Authors](#authors)


## Description

eCommerce backend refactored to use MySQL and sequelize to model and route the database. The structures built in this project allow for seamless CRUD operations within the database, allowing the client to get all products, tags, and categories, along with how they are related to one another. Client may now manipulate, add, or delete data off of the MySQL database within a responsive and organized structure. 

--------------------------------------------------------
### User Story
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

### Acceptance Criteria
```
GIVEN a functional Express.js API

WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize

WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data

WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database

WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON

WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Dependencies

```
"dotenv": "^8.6.0",
"express": "^4.17.1",
"mysql2": "^2.1.0",
"sequelize": "^5.21.7"
```

## Installing

* Fork this repo and clone to your machine
* `npm i` to install all dependencies


### Executing program

* Open terminal in root
* enter `npm i` in command line for dependencies
* login to mysql using `mysql -u root -p` in command line
* enter `SOURCE db/schema.sql` and quit mysql shell
* `npm run seed` to seed the database
* `npm start` or `nodemon server.js` to start program
* test routes in insomnia using `localhost:3001/api/...`

## DEMOS

### CATEGORIES
Demonstration of the following:

- `GET` all categories
- `GET` a single category by its `id` 
- `POST` a new category
- `PUT` to update a category by its `id`
- `DELETE` to remove category by its `id`




https://user-images.githubusercontent.com/100460009/186042248-cb463762-0abb-4a56-a6f7-a26dcc95a708.mp4





--------------------------------------------------------------------------------------------
### PRODUCTS 

Demonstration of the following:

- `GET` all products
- `GET` a single product by its `id` 
- `POST` a new product
- `PUT` to update a product by its `id`
- `DELETE` to remove product by its `id`




https://user-images.githubusercontent.com/100460009/186042395-cc4fbcbc-2824-4fcc-aad9-8d998e764f3f.mp4




---------------------------------------------------------------------------------------------
### TAGS

Thoughts video demonstrates the following functions: 

- `GET` to get all tags
- `GET` to get a single tag by its `id`
- `POST` to create a new tag 
- `PUT` to update a tag by its `id`
- `DELETE` to remove a tag by its `id`



https://user-images.githubusercontent.com/100460009/186042373-33dd3791-0a3c-4f54-abbd-4d2ae7958206.mp4


--------------------------------------------------------------
