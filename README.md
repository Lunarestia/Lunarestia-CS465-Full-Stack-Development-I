# CS465 - Full Stack Development I

* `Module 1` Intro and setup for MEAN. Importing Static HTML Mockup with Express into Node.js

* `Module 2` MVC Routing

* `Module 3` Converts Static HTML to Templates with JSON

* `Module 4` Created and Populated MongoDB NoSQL Database with Mongoose & created Schemas

* `Module 5` RESTful API

* `Module 6` SPA - Single-Page Application with Angular

* `Module 7` Adds Security & Authorization to Add-Trips & Edit-Trips, Requires Users to login for these Buttons to Show & Function.


# Architecture

## Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA)
Express is used more for back end functionality and Angular is used more for front end functionality. Angular is used for Single page applications with each page's code in its own folder in the hierarchy. This is only viewable on the admin side, not the side that the end user sees with Express. Javascript is used for the models, routes, controllers and the main app file.

## Why did the backend use a NoSQL MongoDB database?
NoSQL not relying on a Schema makes it easier to store data, since you can leave some fields blank if needed to fill in later. It is also easier to add to since the data is not fixed, so with this, other data could be added such as rooms, or meals.

# Functionality

## How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
JSON is mainly used for storing data, which is used to transfer data from the backend to the front end client side. Javascript is used here to convert the JSON data but has other uses as well.

## Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.
Adding handlebars functionality made things much more efficient, utilizing partials for the headers and footers of hte HTML documents so there was less code needing to be pasted in multiple files, it could simply be called from these partials.

# Testing

## Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.
The API endpoints were where requests for information were sent to when testing. We used functions like GET, POST, PUT and DELETE. these functions can be used to get information from the database, push information to the database, edit information that is there, and delete information from the database. Adding security is essential to keep unauthorized users from being able to access the information stored there as well as prevented anyone from changing, adding or deleting information stored there without the proper authorization.

# Reflection

## How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
This course has given me a taste of web development and full stack development. I found it very challenging and interesting. I actually would like to learn more and possibly see if this is a type of career I would like to pursue. Throughout this course I feel like I have added to my skillset. Full Stack skills are a desirable set of skills to have in the field of computer science even if you are not working directly in web development. Full Stack skills give you a lot of well rounded knowledge. HTML and CSS help you work with and make a front end site look pleasing. JavaScript can make it look even better for the end user and improve their interaction with the site, so it is a good skill to add. The language used for back end coding, could be something like Python or PHP. Lastly the database that will store everything will need JSON and something like MongoDB NoSQL. So a lot of skills go into making a full stack application, even one that is a single page. 
