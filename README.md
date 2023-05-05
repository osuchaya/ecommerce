# ecommerce

Since this is not a deployed site, please view the walkthrough video at 

Please see the repository where this project is lcoated at https://github.com/osuchaya/ecommerce

## Code source
Starter code was given. This code can be found in this repository: https://github.com/coding-boot-camp/fantastic-umbrella

## Technology Used
| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| Node.js    | [https://nodejs.org](https://nodejs.org) | 
| Sequelize | [https://www.npmjs.com/package/sequelize](https://www.npmjs.com/package/sequelize) |
| JavaScript | [https://developer.mozilla.org/en-US/docs/Web/JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) |
| Express.js | [https://www.npmjs.com/package/express] | (https://www.npmjs.com/package/express) |
| dotenv |[https://www.npmjs.com/package/dotenv]|(https://www.npmjs.com/package/dotenv)|
| MySQL2 |[https://www.npmjs.com/package/mysql2]|(https://www.npmjs.com/package/mysql2)|
| Insomnia | [https://docs.insomnia.rest/insomnia/send-your-first-request] | (https://docs.insomnia.rest/insomnia/send-your-first-request) |

## Description
This project is part of Module 13 on Object-Relational Mapping (ORM) where the author utilized Sequelize package to connect Express.js API with a MySQL database. Here, a dotenv package is also used to store sensitive data such as MySQL username, password and database name, which is git-ignored hence not visible in the repository to the public. In this challenge, Sequelize Models are used to create relationships between Models in the database. The database, as exemplified here as e-commerce one, can be modified through CRUD operations/methods and such modification can be done via Insomnia as a medium to interact with the back-end code. 


## Installation and Usage
Install Node version 16.0 in order to run this application successfully. Please ensure to have the following packages installed as listed in package.json file: MySQL2, Sequelize, dotenv and Insomnia for testing purposes. Upon successful installation, run the app by typing 'npm start' in the Integrated Terminal. Initialize the database by doing the following in integrated terminal: 
1. Type mysql -u root -p
2. Type in your password for MySQL
3. Type SOURCE schema.sql;
4. Type SOURCE seeds.sql;
5. Type Quit;
6. Type in integrated terminal 'npm run start'
7. Test by typing in Insomnia Core e.g. for GET route to view all elements in categories, type in http://localhost:3001/api/category   please not that your port number can be different to 3001. Please check in your server.js file and modify accordingly.


## License
This project is currently under GPL3.0 license.

## Learning points
The author has learnt from module 13 on Object-Relational Mapping (ORM) to connect to a database using Sequelize and environment variable (.env file), to work with and configure a Sequelize model as well as performing CRUD operations on the model.

## Credits
Resources were consulted to complete this application such as the documentations on how to use Sequelize, dotenv, mysql2. See links below:
https://sequelize.org/docs/v6/core-concepts/model-querying-basics/
https://sequelize.org/docs/v6/other-topics/sub-queries/
https://docs.insomnia.rest/insomnia/send-your-first-request
https://www.npmjs.com/package/dotenv
https://www.npmjs.com/package/mysql2





