<<<<<<< HEAD


# PHP JavaScript Developer Test

A simple test for PHP / JavaScript Developers

## Instructions

1. Fork or clone this repo
2. Write a script to Import the CSV file located in `data/customers.csv` into a database (MySQL or Mongo is preferred)
3. Create a basic PHP web service that serves the data from the database as JSON
4. Create a basic web page that asynchronously loads the JSON into a list or table when you click a button
5. If you are completing this test as part of a job application please include a zip file of your project (including git config/metadata) with your application otherwise create a pull request and we'll take a look :)

### Guidelines

1. Your repo needs to include at minimum anything required to get the app working.  Detailed instructions should be provided in the `README.md` file to setup and run the app.
2. If a structured schema migration tool is not used then a setup script must be supplied to create any data tables etc
3. Try not spend more than 2 hours on it

### Bonus Points

* Make it Pretty
* Make it as OO as possible
* Consume dependencies with tools like Composer, Bower and NPM
* Use patterns like MVC, ORM
* Compile any front end assets with a build tool like gulp
* Unit tests

# php-js-dev-test
A simple test for PHP / JavaScript Developers

<pre>
Please install Laravel framework
version. Laravel Framework 5.6.29

csv importing function
http://localhost:8000/customerimport

web service api link for display all customers
http://localhost:8000/api/customers

Display customer table
http://localhost:8000/api/customerlist

*ReAct 
*Webpack compile

Schema DB<br/>
php artisan migrate:install
php artisan make:migration create_customer_table<br/>
database/migrations/2018_08_04_120905_create_customer_table.php

Model 
app/Customer.php

Controller
app/Http/Controllers/customerController.php

View
resources/views/customer.blade.php
</pre>
