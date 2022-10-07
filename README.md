
   

Q2) What is NPM?
=>Npm Stand for Node package managar its a standerd library use to install node packages in our project.
we have to install NPM every time in every project

           
Q3) What is node.js ?.
=>node is a single thread,open source, cross platform backand javascript run time enviroment that helps to execute javascript code outside a wegb browser .
i run on javascript engine.

           
Q4) What are the different modules in Node.js?.

=> Node module is a functionality  in node js it iws a javascrpit file wh9ichj contains functions.
This node module can be reuse.
 there are rthree types pof module 
=> Core module 
=> local Module
=> third Party Module

Q5) Core  module?.             
 core module is light weight and con5tain less functions 
 such as 
 HTTP.
 URL.
 Path.
                            
                
Q6) What is the purpose of the module.exports?.
 =>The main purpose of module. exports is to achieve modular programming. Modular programming refers to separating the functionality of a program into independent, interchangeable modules, such that each contains everything necessary to execute only one aspect of the desired functionality.

              

Q7) Difference between default export and named export?. 
        
=> in default export every function will export from the file and we can use each and every function but in name export we only send named function name export can send only particular name function and no other functiuons will work till they get export.

             
Q8) How do you import any module in Node.js?.
=>To import our own Node JS module.
var express = require("express");
To import existing Node JS Module Import Node JS “express” module;
var arthmetic = require("express");
Import Node JS “mongoose” module; 
var mongoose = require("mongoose")

              
       
Q9) What are the different types of HTTP requests?.
=>HTTP (Hypertext Transfer Protocol).
specifies a collection of request methods to specify what action is to be performed on a particular resource.
 The most commonly used HTTP request methods are GET, POST, PUT, PATCH, and DELETE. 


Q10) Explain the concept of middleware in Node.js?.
=>Express.js is a routing and Middleware framework for handling the different routing of the webpage and it works between the request and response cycle.
Middleware gets executed after the server receives the request and before the controller actions send the response.
Middleware has the access to the request object, responses object, and next, it can process the request before the server send a response.
 An Express-based application is a series of middleware function calls.

 Q11)Explain CORS?.
 => CORS is a mechanism that uses additional HTTP header to inform a browser to allow a web application running at one origin (domain) have permission to access selected resources from a server at a different origin. 
  

Q12)What is Express. how it helps you to create a backend application?.
=>  Express is a node js web application framework that provides broad features for building web and mobile applications. It is used to build a single page, multipage, and hybrid web application.
It's a layer built on the top of the Node js that helps manage servers and routes.

const express = require('express')
const app = express();

app.get('/',(req,res)=>{
        res.send("welcome to my world")
});

app.listen(4000, ()=>{
        console.log("port is running)
});

Q13) Explain min 5 status codes gets used in Backend development?.

=> 404 Not Found
   403 Forbidden
   500 Internal Server Error
   503 Service Unavailable
   504 Gateway Timeout


Q14) Difference between HTTP and HTTPS?.
=> HTTP stands for HyperText Transfer Protocol and HTTPS stands for HyperText Transfer Protocol Secure.
In HTTP, URL begins with “http://” whereas URL starts with “https://”
HTTP uses port number 80 for communication and HTTPS uses 443
HTTP is considered to be insecure and HTTPS is secure
HTTP Works at Application Layer and HTTPS works at Transport Layer



Q15) How do you create a simple Express.js application?.

                const express = require('express')
                const app = express();

                app.get('/',(req,res)=>{
                        res.send("welcome to my world")
                });

                app.listen(4000, ()=>{
                        console.log("port is running)
                });

@16) Implementation of all type of exports in backend application?.

=>  default Export
        const Mycomponent =()=>{}
        export default Mycomponent;
   
   Named Export
         
         export from Mycomputer.js file
         export const Mycomponent = ()=>{}


