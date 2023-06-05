
# Code 401 - Advanced JavaScript 

1. [Reading Class - 1](#class-1-reading-notes)
<br>

2. [Reading Class - 2](#class-2-reading-notes)

## Class 1 Reading Notes:

### 1. How would you describe Node to a non-technical friend?

Node. js is a runtime environment for executing JavaScript code. Node is used extensively for server-side programming, making it possible for developers to use JavaScript for client-side and server-side code without needing to learn an additional language
<hr>

### 2. What does it mean that Node is a JavaScript runtime?
it means that it provides an environment for executing the code
outside the browser
<hr>

### 3. What is Node used for?
Node used to write server-side applications with access to the operating system, file system, and everything else required to build fully-functional applications.

<hr><hr>

## Class 2 Reading Notes:


### Explain middleware, answer as though I were a non-technical recruiter.

Middleware is software that lies between an operating system and the applications running on it.  middleware enables communication and data management for distributed applications.

### Express the most popular __ __ ____.
Node.js framework


### Express is “unopinionated.” What does that mean?

Express gives you the freedom to make your own decisions and and you can create your application according to your specific needs and preferences.

### What is a module and why is modularity useful to us as developers?

it makes your code easier to read because it means separating it into functions that each only deal with one aspect of the overall functionality. It can make your files a lot smaller and easier to understand .

### What version of npm are you running on your machine?

9.5.0

### What command would you type to install a library/package called ‘jshint’ into your node project?

npm install jshint


### Explain why tests are important. Please explain as though I were your non technical elder. 

if you are working on something then you got the final result . and u discover that you have alot of problems in the structure ,it will be a big problem because u will waste lot of time trying to fix it . thats why the test step by step is very important

### What are three expected benefits of testing

1- Bug Detection and Prevention
<br>
2- Save time
<br>
3- Cost Savings

### Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.

Individual Pitfalls:

1- Lack of Test Prioritization
<br>
2- Lack of Test Coverage
<br>

Team Pitfalls:

1- Lack of Collaboration
<br>
2- Inconsistent Testing Standards
<br>


### What are three benefits of Continuous Integration?

1- Improved Code Quality and Stability
<br>
2- Early Detection of Integration Issues
<br>
3- Faster Feedback and Faster Release Cycles

### What is the difference between Continuos Delivery and Continuous Deployment?

In Continuous Delivery, the software is continuously built, tested, and prepared for release throughout its development lifecycle. The focus is on ensuring that the software is in a deployable state at any given point.

<br>

Continuous Deployment takes automation a step further. In addition to the continuous build, test, and preparation for release, Continuous Deployment automatically deploys the software to the production environment once it passes all necessary tests and quality checks.

### Explain how GitHub fits into this process assuming the listener comes from a non-technical background

GitHub is a platform where developers store and manage their code. It integrates with other tools to automate processes like testing and deploying software changes. It serves as a central hub for collaboration and ensures that code is efficiently delivered or deployed as part of Continuous Delivery and Continuous Deployment processes.


### What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?

Time Complexity Big(o)

### How can we ensure that we’ll avoid an infinite recursive call stack? 

Base Case enure that your recursive function has a base case , a base case represents the condition under which the recursive calls should stop and the function should return a result
