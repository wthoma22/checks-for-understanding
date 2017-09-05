## Week Three - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. At a high level, what is Node?
  On a high level, node allows the creation of web servers using javascript and modules.

2. What is Express? Why is Express similar to in the Ruby world?
    Express is a web application framework for node and is similar to Sinatra in Ruby.

3. How do we setup a route when creating an API with Node and Express? Please provide a code snippet.
    To setup a route when creating an API with Node and Express we create variables and then send a GET request to the page. In this example, we are sending the text 'hello world' to the page.
    
    var express = require('express')
    var app = express()

  app.get('/', function (req, res) {
    res.send('hello world')
  })

4. What do we use Knex for?
  Knex is used to write raw SQL in JavaScript.

5. How could you organize your code to follow the MVC design pattern in your Quantified Self project?
  You could organize your code to follow the MVC design patters by creating models and controllers for your JS code.

6. How do you execute raw SQL in node?
  You could add a database variable requiring knex and return the response similar to the example below:

  const database = require('knex')(configuration);

  function getAll() {
    return database.raw('SELECT * FROM foods').then(function(response) {
        return response.rows
    })
  }

7. What are some advantages to having your front end and back end code live in separate applications? What are some disadvantages?
  Advantages: Easier to read. Cleaner code. Seperate responsibilities. Can have two team on seperate parts of project.
  Disadvantages: Have to build out endpoints. Multiple servers running.

#### Review  

8. Describe DNS.
  DNS or Domain Name System is the Internet's system for converting alphabetic names into numeric IP addresses. 

9. What does writing clean code mean to you?
  Having well organized code in an MVC archetectural style. Using DRY principles. Making it easy for next developers on projects to easily take on and change code.

10. If you were building an application that models hotels, what classes would you need? What classes would be responsible for what functionality?
  Classes for rooms, reservations, guests, etc..
