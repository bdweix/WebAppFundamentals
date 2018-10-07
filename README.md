# Fundamentals of Web Applications
The purpose of this course is to understand the fundamentals of a fullstack web application. Subjects include the types of web requests, roles of the frontend and backend, basics of HTML, storing data, and starting an Express project.

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
Objective: Understand the basic types of web requests used to communicate and how they differ. By the conclusion of this section, students will be able to differentiate between different HTTP requests and formulate their own based on given criteria. 

- Headers
- Versions (1.1)
- Body
- Status Codes (404, 401, 200, etc)
- Routing/Paths

## 2. NodeJS/Express Overview
Objective: Learn and understand how to install and set up a fresh Express project. By the end of this section, students will understand how to link into a class repository and how to use NPM and the CLI for Express.

- Installing Express
- CLI options
- Connecting to GitHub
- NPM 
- Starting the server

## 3. Requests/Responses
Objective: Introduce the idea of sending requests and receiving responses over HTTP. Using an API developmenet enviroment ([Postman](https://www.getpostman.com/)), students will communicate with their localhost to a simple GET + POST route in their Express application. Will integrate understanding of request types and demonstrate the fundamentals of a web app. No HTML or views will be rendered at this point.

- How to write GET and POST routes in Express
- Use Postman/Paw/cURL/Rested
- Form Data input, raw output 
- How to view headers 
- How to return different status codes

## 4. HTML
Objective: Understand the basic structure of HTML documents as a function of displaying data. By the end of this section, students will feel confident building HTML pages in an IDE and rendering them in the browser without using a server.

- Ties together routes, requests, and responses with HTML
- Tags (HTML, BODY, P, A, IMG, DIV, SPAN)
- Classes + IDs
- How to structure a paage

## 5. CSS
Objective: Understand how CSS can be added to an HTML document in order to control the visual styling of elements.

- Styling Options
- Class/ID Selectors
- Hover States

## 6. Backend + Frontend
Objective: Understand how to combine backend skills with frontend skills to use a server to render HTML documents.

- Hosting HTML/CSS inside of an express app
- Passing data from a controller to a view
- Returning a view from a route

## 7. Forms
Objective: Understand how forms work (from an HTML perspective) and understand how they can be used to create HTTP POST requests. By the end of this section, students will understand the different types of inputs and how they relate to HTTP POST requests.
  
- Form Tags
- Action + Method Attributes in Form Tags
- Submitting Forms
- Input Types (Number, Text, Textarea, Select)

### Forms Part 2:
Students will then be expected to inspect the data upon form submission and make a decision based on the data. The method will then return a new view with specified data.

- Receive Data
- Modify Data
- Return Response View with Data

## 8. Databases + MVC
Objective: Understand databases as a way to persist data throughout an application. This will make it possible for students to build more complicated sequences. Each student will be given credentials to their own private database.

- Students given private database (EC2 instance with login credentials)
- Introduction of Models (no relationships)
- Using the ORM or Raw SQL Queries
- Using database data within views
- Migration Basics

## 9. Final Project
Students should be able to build a personal "profile" page. This will feature their picture and basic facts about themselves such as hometown, favorite books, songs, animals, etc. Information will be stored on their database and passed to their view. Students should be able to edit and delete data from within their page.

## Other Topics, a plethora of other things that can **now** be taught or explained:
- React + Vue: show the use cases for this and how a virtual dom can benefit users (why reload the entire page?! It all makes sense when you just spent 3 months making painstaking webpages).
- Frontend Javascript/JQuery: adding interactivity without React + Vue
- Bootsrap: why write your own styling? Use professionally developed CSS that automatically adapts to orientation and size changes.
- Test Driven Development: building applications that think about testing from the beginning. 
- Web Hosting: going from local development to production servers and utilizing AWS and other services to host every part of your stack in the cloud
- Queues: offloading intensive tasks to background workers
- Caching: making use of Redis and the browser to increase page loads
- CDNs: distributing content around the world 
- Git Management: how to work with a larger team on Git
- Agile Development Methods
