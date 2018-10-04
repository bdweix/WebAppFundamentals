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
8. Databases (potentially)
9. Final Project
### Lab:
Using their unqiue credentials and an API developmenet enviroment (see [Postman](https://www.getpostman.com/)), students would complete weekly assignments interacting with a production API. Activities would include basic CRUD operations and the eventual integration into their project.

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
Objective: having understood the ability to send and receive data over their Express server, HTML will be introduced as a way to send structure content as data.
- Ties together routes, requests, and responses with HTML
- Tags (HTML, BODY, P, A, IMG, DIV, SPAN)
- Classes + IDs
- How to structure a paage

- HTML
    - Use HTTP language throughout to create mental pathways
    - Tags
        - html
        - body
        - p
        - a
        - etc
    - Classes and IDs
    - How to layout a page 

- CSS
    - Class selectors
    - ID selectors 
    - Hover states

- Tie together backend + frontend
    - How to host HTML/CSS inside of an express app
    - How to return the view from a route 
        - Learning objective: To realize that hosting statically and hosting with SSR doesn't look/feel any different 

- Forms
    - Action + Method attributes in <form>
        - Tie back into the same concepts of HTTP requests/responses
    - Submit 
    - Input Types
        - Number
        - Text
        - Textarea 
        - Select 

- How do forms connect to the backend?
    - Submitting a form 
    - Inspecting the data upon submission 
    - Acting on the data
        - Returning a new view 
        - Returning the data

---After this point, it's unclear if the rest of the material will fit into the timeline---

- Databases
    - Students are given their own Database
        - EC2 instance 
        - Each user gets a database with their name 
        - Every user 
    - Connecting to Express models 
    - How to use the ORM
    - Migrations

- Final project 
    - Design a profile page 
    - Should include tables for:
        - Favorite books
        - Favorite songs 
        - Favorite animals 
    - All tables are editable 
        - delete 
        - create 
    - Should also contain inputs for:
        - Name
        - Email 
        - Age
        
- What's out there - React + Vue and where it falls. MVC 

