
# Express REST API

## Classes are a template for creating ____.
 objects

 ## Can a class declaration be hoisted?

 No, a class declaration cannot be hoisted in JavaScript.

 ## How would you describe a constructor and contextual “this” to a non-technical friend?

 constructor is a thing that give you the ability to create objects from it instead of creating objects from scratch using new keyword
 and (this) refers to the current object being created you assign the passed values to the properties of the object.


## Within Express, what does routing refer to?
refers to determining how an application responds to a client request to a particular endpoint, which is a URI (or path) and a specific HTTP request method (GET, POST, and so on).

## What is the difference between a route path and a route method?

Route path: its a part of the website url ('/user') and its string and it will request a specific website page 

Route method: its a method that we create to take a path and send a request the take the respone to us after we use it , it could be (get,post,put,delete)



## When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

we use next as a paramete in route handler to execute the next middleware if it exsit , and if next has been passed to your middleware as a parameter, it is your responsibility to call it when you want to pass control to the next middleware or route handler


## What is an Express Router?

Router is like a mini-Express application. It doesn’t bring in views or settings but provides us with the routing APIs like .use, .get, .param, and route.

## By what mean do we initialize express.Router() in an express server?

To initialize an Express Router in an Express server, we use the express.Router() function



## What do we use route middleware for?

Route middleware in Express is a way to do something before a request is processed. This could be things like checking if a user is authenticated, logging data for analytics, or anything else we’d like to do before we actually spit out information to our user.