# Ecommerce Backend

## Description

This assignment was made with the purpose of connecting sequelize to node.js so that the data in the database would present itself in insomnia. In order for everything to run smoothly, it was necessary to make sure that everything in the routes folder, the seeds folder, and the models folder were written precisely since I had a lot of run ins with things not being written appropriately. So I tried to approach the project with mindfulness.

`````````````````
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
``````````````````

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributions](#contributions)
- [License](#license)
- [Tests](#tests)
- [Questions](#questions)

## Installation

First you must do "npi install" or "npm i" to install the packages and node_modules.

## Usage

After "npm i" is entered, run the seeds folder by entering "node seeds/index.js" where all the seeds files are being run. After that, we run the server by entering "node server". At this point, all the seeds files should show accordingly with no errors, including the schema and the parameters that were entered. After your port is being run, go to insomnia to test out the GET, POST, PUT, and DELETE requests. If you haven't done so already, you'd have to download Insomnia into your desktop. Navigate to the appropriate http requests by entering "http://localhost:3001/api/categories" for example. All the JSON data for "categories" should be displayed, and the same can be done for "products" and "tags".

## Contributions

N/A

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Tests

N/A

## Questions

- Github: https://github.com/jmaduafo

## Screen Recording

[object-oriented programming.webm](https://github.com/jmaduafo/Ecommerce-Backend/assets/87540591/9aa1eebc-699e-4480-a137-8781e659c7fb)


