# e-commerce backend 

## Description 

---

E-Commerce Backend is a product that uses an Express.js API and uses Sequelize to interact with a MySQL database. This project entails seeding information from a database, running the application's server, and performing a variety of GET, POST, PUT, and DELETE requests for the tag, category, and product routes in Insomnia. For further information about this application and how to use it, please visit my GitHub repository [here]().

## Table of Contents 

---

- [Installation](#installation)
- [Usage](#usage)
- [Demonstration](#demonstration)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation 

---

Please follow the steps outlined below to install this application and get the development environment up and running on your local device:

1. Before you begin, ensure that you have Node.js installed on your local machine. Follow the instructions listed [here](https://nodejs.org/en/download/) to download and install Node.js.

2. You will also need to install MySQL and have a MySQL account created on your local machine. Follow the instructions [here](https://www.npmjs.com/package/mysql2) to help you!

3. You will also need to install Insomnia on your local device to run all of the requests for routes.

4. In your terminal, use the command git clone and paste the link to this repository so that you can clone it to your local machine.

5. Then run the command "npm init -y" to install Node Package Manager.

6. Next run the command "npm i inquirer" to install Inquirer and its associated dependencies.

7. Be sure to run the command "npm install sequelize" for Sequelize and "npm install dotenv --save" for the dotenv package. This is critical to use environment variables to store sensitive data like your MySQL username, password, and database name. 

## Usage

Please follow the steps outlined below for how to use the command-line application once all of the necessary programs and npm packages are installed:

1. Be sure to sign into your MySQL account and run "source db/schema.sql" to generate the tables in the database. 

2. Next you need to seed your databse and run the command "npm run seed".

3. To begin using the application, run "node server.js" in the command line. 

4. You will have then have the ability to run requests for all of the routes in Insomnia. You can add, update, and delete information for products, categories, and tags.

## Demonstration

---

Please watch this [video tutorial](https://drive.google.com/file/d/1nPDG-bbBFPpuEbeGavvNOsv0O3SmRPYd/view?usp=sharing) for a demonstration of how to use the E-Commerce Backend application step by step. You will also be able to see GET, POST, PUT, and DELETE requests for all of the routes created for tags, categories, and products. 


## Contributing 

---

Caitlin O'Reilly is the primary contributor of this Team Profile Generator. If you are interested in contributing to this project, you are welcome to fork it.

## Questions 

---

---

If you have any questions about this project, please feel free to contact me directly via email at coreilly29@gmail.com.
You can also view my additional projects at https://github.com/caitoreilly.