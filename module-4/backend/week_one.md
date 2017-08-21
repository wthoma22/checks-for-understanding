## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's the most useful thing you learned from completing the intermission week work?
  The most useful thing I learned from completing the intermissionw week work was basic Javascript fundamentals.

2. What are some tools to help debug JavaScript code?
  Debugger and console.log(error)

3. What are some tools you need in order to unit test your JavaScript?
  Mocha

4. What is the syntax for invoking a function?
  functionName()
  
5. What's the difference between `==` and `===` in JavaScript?
  == shows that the two have the same value
  === shows that the two have the same value and same Type

6. What's the difference between asynchronous and synchronous JavaScript? 
  Synchronous JS waits for each operation to complete to executes the next operation.
  Asynchronous JS executes all operations in the first GO only. The result of each operation will be handled once the result is available.

7. What's a callback function and what are some reasons when we use/need callback functions?
  A callback is a function to be executed after another function is executed. For example, if you have a function a running then function b, function a could take longer to load which would make function b run first. You can use a callback to ensure function a runs first before function b is executed.

8. What's the biggest difference between a promise and a callback?
  A promise is either pending, fulfilled, or rejected. After being created if fulfilled, it will do a .then(on-fullfillment) and return the promise. If rejected, it will go to a .then/.catch and then return.

9. How do we setup a route when creating an API with Node and Express?
  N/A

10. What's `npm` and what do we use it for?
  NPM makes it easy for JS developers to share and reuse code. Bits of reuseable code are called packages and they contain a directory with one or more files inside.

#### Review  
11. What's the MVC design pattern? Describe each part of MVC?
  The MVC design pattern stand for Model View Controller. The model is the central component of the pattern that manages the data and logic of the app.The controller accepts input and converts it to commands for the model or view. Lastly, the view is the output representation of information.

12. What is AJAX? What are some benefits of using AJAX?
  AJAX is Asynchronous JavaScript And XML.Some of the benifits are that it reduce the traffic travels between the client and the server, you can populate data on the page from a database, and the response time is faster.

13. What's a background worker? When would we want to use a background worker?
  A web worker is a JavaScript that runs in the background, independently of other scripts, without affecting the performance of the page. You can continue to do whatever you want: clicking, selecting things, etc., while the web worker runs in the background

