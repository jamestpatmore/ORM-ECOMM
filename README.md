# ORM-ECOMM (Object-Relational Mapping (ORM): E-Commerce Back End) :magic_wand:

![javascript](https://img.shields.io/badge/Javascript-yellow)
![node.js](https://img.shields.io/badge/-node.js-green)
![screencastify](https://img.shields.io/badge/-screencastify-lightgrey)
![json](https://img.shields.io/badge/-json-orange)
![sequelize](https://img.shields.io/badge/Sequelize-blue)
![express](https://img.shields.io/badge/express-orange)
![dotenv](https://img.shields.io/badge/dotenv-green)

## Description 
A mySQL database application for an ECommerce backend using express to create the server and Sequelize/mySQL to create the database while still using javascript code on the server side :chess_pawn:

For the video walkthrough explaining the functionality of the application go [here]() :clapper:

## User Story 
```md 
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptence Criteria 
```md 
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

## Installation 
This is a server side application so using Insomina is a great tool to test the routes you can also use Postman if you'd like :incoming_envelope:

With that being said I will go one by one with the proper dependency installations that must take place :old_key:

Express 
```md
npm i express
```

Dotenv
```md
npm i dotenv
```

Sequelize
```md
npm i sequelize
```

mySQL2
```md
npm i mysql2
```

## Usage 
:dna:
Run the following command at the root of the project then use the database how you please (through insomnia/postman) :joystick:

```md
npm start
```

## Contact
[Email](mailto:jamesthomaspatmore7@gmail.com)
</br>
[Github](https://github.com/jamestpatmore)