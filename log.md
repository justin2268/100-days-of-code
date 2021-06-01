# 100 Days Of Code - Log

## Day 1: May 24th, 2021


**Today's Progress**: Began FreeCodeCamp's Javascript Algorithims and Data Structures Course. 
It's mostly revision on basic Javascript but its great practice.
Completed the first challenge, making a shopping list with nested arrrays.

**Thoughts:** 
I like this style of learning to program because the roadmap is more clearly laid out in front of me.


**Link to work:** 
https://github.com/justin2268/100-days-of-code


## Day 2: May 25th, 2021
**Today's Progress**: Continued FreeCodeCamp's JSA+DS course. 
Continuing to work through Udemy Web Developer Course looking at using JS to change HTML and make web pages more interactive.


**Thoughts:** 
Enjoyed working through the JS project today with the Udemy course. Need to do some more maths work in addition to programming.

**Link to work:** 

https://github.com/justin2268/Dicee-Challenge---Starting-Files-2

## Day 3: May 26th, 2021
**Today's Progress**:
Callbacks were part of today's lessons and as I understand it they are a function which is passed into another function which enables the function to be called from outside of the function wthin which it is called, this allows for asyncronous programming
Began learning more about Node.js and how it can be used to create programs as well as power the back end of Web Development.
**Thoughts:** 

### Day 4: May 27th, 2021
**Today's Progress**:
Started a Node.js project, initilised a git repo and linked the remote repo with node. 
Learned about express 'npm install express', require.


## Day 5: May 28th, 2021
**Today's Progress**:
Express 
The "/" location is the root of a webpage.
### This is a function of the app we have created which is triggered when someone tries to access the home route, then our callback gets called with the functionality we want

**get in this case is a http request method**

app.get("/", function(req, res){
    res.send("Hello");
})
Can send html through the send
### understanding and working with routes

Started using nodemon to make developing faster by monitoring for changes in code on saves.

### __dirname
serves up the current path for the file you want to use

### Body Parser 
Allows us to access form data
npm install body-parser
const bodyParser = require("body-parser");

### Calculator
Completed a calculator that is all run in the back end with JS, express.



## Day 6: May 29th, 2021
**Today's Progress**:

### API
API's have endpoints which are a HTTP request 
Paths and Parameters help filter the results of the API resulting in a different url for the API's endpoint

http://api.openweathermap.org/data/2.5/weather?id=2147714&appid=6a39b94dc021b31125a89c27a34e3237&units=metric

const express = require("express");

const app = express();

app.get("/", function (req, res) {
    res.send("hello")
})
app.listen(3000, function () {
    console.log("Server started at port 3000");
})

## Day 7: May 30th, 2021
**Today's Progress**:
Further work on API's. 

app.post using bodyparser 

## Day 8: May 31th, 2021
**Today's Progress**:
Using Heroku to create a live website
Make sure the project has a Procfile >> web: node app.js
Then use heroku create
git push heroku master

## Day 9: June 1st, 2021
**Today's Progress**:
Set up a new development evironment on another laptop as practice.
Set up a node server using express

.gitignore # to comment
list files that need to be ignored including their extensions
*.txt removes all .txt files
