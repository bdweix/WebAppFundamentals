# Fundamentals of Web Applications
Understand the fundamentals of a fullstack web application. Subjects include the types of web requests, roles of the frontend and backend, basics of HTML, storing data, and starting an Express project.
### Main Topics:
1. HTTP Requests
2. NodeJS/Express Overview
3. Requests + Responses
4. HTML
5. CSS
6. Frontend + Backend
7. Forms
8. Databases
9. Final Project
### Lab:
Using their unqiue credentials and an API developmenet enviroment (see [Postman](https://www.getpostman.com/)), students would complete weekly assignments interacting with a production API. Activities would include basic CRUD operations and the eventual integration into their project. This would simulatenously provide an introduction to a database that will be covered in Topic 8.

## 1. HTTP Requests
Objective: understand the basic types of web requests used to communicate. Main types are GET, POST, PUT, DELETE, HEAD, PATCH, OPTIONS.
- Headers
- Versions (1.1)
- Body
- Status Codes (404, 401, 200, etc)
- Routing/Paths

## 2. NodeJS/Express Overview
Objective: students will install and set up a fresh Express project using a class defined template. They will link into a class repository and learn the basics of NPM and CLI for Express.
- Installing Express
- CLI options
- Connecting to GitHub
- NPM 
- Starting the server 

## 3. Requests/Responses
Objective: introduce the idea of sending requests and receiving responses over HTTP. Using an API developmenet enviroment ([Postman](https://www.getpostman.com/)), students will communicate with their localhost to a simple GET + POST route in their Express application. Will integrate understanding of request types and demonstrate the fundamentals of a web app. No HTML or views will be rendered at this point.
- Use Postman/Paw/cURL/Rested
- Form Data input, raw output 
- How to view headers 
- How to return different status codes

## 4. HTML
Objective: having understood the ability to send and receive data over their Express server, HTML will be introduced as a way to send structure content as data. Pages will be built outside of the application using a text editor.
- Ties together routes, requests, and responses with HTML
- Tags (HTML, BODY, P, A, IMG, DIV, SPAN)
- Classes + IDs
- How to structure a paage

## 5. CSS
Objective: now being introduced to HTML without any styling, show the use case and benefits of CSS and how you can modify HTML for better presentation. Pages will be built outside of the application using a text editor.
- Styling Options
- Class/ID Selectors
- Hover States

## 6. Backend + Frontend + MVC
Objective: students will now have an understanding of how to pass data to and from their Express application. Students will also understand how to build a basic HTML/CSS webpage. Bringing these together, students will make a simple GET route that now returns HTML (server side rendering) instead of plain data. This is the basics of the web. Model View Controller will be introduced as a way to interact with objects and data.
- Hosting HTML/CSS inside of an express app
- Passing data from a controller to a view
- Returning a view from a route

## 7. Forms
Objective: students are now able to build and return different webpages through their Express application. Students are also familiar with making simple post requests to their application from Topic 3. Forms will be introduced as the browsers way of making POST requests to an application. This will also introduce the new HTML tag of a <form> and the types of inputs allowed.
- Form Tags
- Action + Method Attributes in Form Tags
- Submitting Forms
- Input Types (Number, Text, Textarea, Select)

### Forms Part 2:
Students will then be expected to inspect the data upon form submission and make a decision based on the data. The method will then return a new view with specified data.
- Receive Data
- Modify Data
- Return Response View with Data

## 8. Databases
Objective: present databases as a way to persist data throughout an application. This will make it possible for students to build more complicated sequences. Each student will be given credentials to their own private database.
- Students given private database (EC2 instance with login credentials)
- Migration Basics
- Introduction of Models (no relationships)
- Using the ORM or Raw SQL Queries
- Using database data within views

## 9. Final Project
Objective: students should be able to build a personal "profile" page. This will feature their picture and basic facts about themselves such as hometown, favorite books, songs, animals, etc. Information will be stored on their database and passed to their view. Students should be able to edit and delete data from within their page.

## Other Topics, a plethora of other things that can **now** be taught or explained:
- React + Vue: show the use cases for this and how a virtual dom can benefit users (why reload the entire page?! It all makes sense when you just spent 3 months making painstaking webpages).
- Frontend Javascript/JQuery: adding interactivity without React + Vue
- Bootsrap: why write your own styling? Use professional styles from pro's with one line of code.
- MVC: unsure if this would be presented throughout this course, but tough on the thinking behind this.
- Relational Databases/ORMS: how can these be utilized with complex business applications
- Test Driven Development: building robust applications
- Web Hosting: going from local development to production servers
- Queues: offloading intensive tasks to background workers
- Caching: making use of Redis and the browser to increase page loads
- CDNs: distributing content around the world 
- AWS/Cloud Services: utilizing AWS and other services to host every part of your stack in the cloud
- Git Management: how to work with a larger team on Git
- Agile Development Methods
