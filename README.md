[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# ORM E-Commerce Back End

## Description

This project utilizes the sequelize package in order to create a back end for an ecommerce website. It creates a database filled with seed products of categories, products, product-tags, and tags. Using the sequelize syntax, models and routes were created to use with the database. Anybody who wishes to use this application can run a variety of requests to the back end including: get all categories/products/tags, get one category/product/tag, create one category/product/tag, update one category/product/tag, and delete one category/product/tag. 

Below is a walkthrough video that will better illustrate how to use this application.

Walkthrough Video:

https://www.youtube.com/watch?v=KC8YGkpflvE

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Questions](#questions)

## Installation

There are a few different steps to getting this application installed and ready to go.

Step 1: Install mysql if you haven't already. Please refer to online documents to get mysql up and running (I used [this one](https://coding-boot-camp.github.io/full-stack/mysql/mysql-installation-guide)).

Step 2: Clone the repo onto your local machine.

Step 3: Create a .env file in the root of the project.

Step 4: In the newly created .env file, set 

DB_NAME='ecommerce_db' 

DB_USER='root' 

DB_PW='(the password you created when you installed mysql)'

You should be ready to move onto usage after these four steps.


## Usage

Continuing from the installation instructions, the following steps will help you use this application.

Step 5: In your terminal at the root of the project folder, run the command

``` 
mysql -u root -p
```

It will prompt you to enter a password. Please enter the password you created when you installed mysql.

Step 6: Run the command

```
source db/schema.sql
```

If there are no error messages, run 

```
quit;
```

Step 7: In your terminal, to seed the test data into the database run the command

``` 
npm run seed
```

Step 8: In order to invoke the application to connect to the database run the command

```
npm start
```

Step 9: Use insomnia or a similar application to test all the various different routes and how they respond to whichever information you desire.

## License

Copyright 2021 Alex Sadrgilany

Permission is hereby granted, free of charge, to any person obtaining a copy 
of this software and associated documentation files (the "Software"), to deal 
in the Software without restriction, including without limitation the rights to 
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the 
Software, and to permit persons to whom the Software is furnished to do so, 
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all 
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, 
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A 
PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT 
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF 
CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE 
OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Questions

[My GitHub Profile](https://github.com/asadg7)

To reach me with questions, please email: asadrgilany7@gmail.com

