# E-Commerce Back End

## Technologies
![Technologies](https://img.shields.io/badge/-Git-F05032?logo=Git&logoColor=white)
![Technologies](https://img.shields.io/badge/-JavaScript-007396?logo=JavaScript&logoColor=white)
![Technologies](https://img.shields.io/badge/-Node.js-339933?logo=Node.js&logoColor=white)
![Technologies](https://img.shields.io/badge/-npm-CB3837?logo=npm&logoColor=white)
![Technologies](https://img.shields.io/badge/-MySQL-4479A1?logo=MySQL&logoColor=white)
![Technologies](https://img.shields.io/badge/-Sequelize-000000?logo=&logoColor=white)
![Technologies](https://img.shields.io/badge/-Dotenv-FFFF00logo=&logoColor=white)


## Description 
This App is to build the back end for an e-commerce site. I will take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

### User Story
```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

### Acceptance Criteria 
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
```
npm i
```
```
mysql -u root -p
source db/schema.sql
exit 
```
```
npm run seed
node server.js
```

![Video](./Assets/Install.gif)

https://www.youtube.com/watch?v=EmBVBUczytA&ab_channel=ANDRESMEJIA

## Testing
Testing of the code was completed in Insomnia

![Video](./Assets/Insomnia.gif)

https://www.youtube.com/watch?v=i7SiLVcrZxc&ab_channel=ANDRESMEJIA

## Licence

- MIT


