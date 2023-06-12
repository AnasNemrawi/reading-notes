
## ES6 Classes

1- Classes are a template for creating objects.

>Creating objects

2- Can a class declaration be hoisted?

> In JavaScript, unlike function declarations, class declarations are not hoisted.

3- How would you describe a constructor and contextual “this” to a non-technical friend?

> a constructor is like a recipe or blueprint that helps create objects with specific characteristics, and "this" is like the word "I" or "me" that refers to the current object being created or used.

## Express Routing

1- **Within Express, what does routing refer to?**

>Routing means the picking a path (endpoint) while navigating the application, picking a certain path will send a request to the server which will be answered with a response for the client.

2- **What is the difference between a route path and a route method?**

>The route method is a type of HTTP requests that defines the protocol of what should be sent back to the user as a response and how the request will be handles, examples are get, post, put, delete methods. While route path is the link(URL path) that will execute or invoke that method handling function once visited, it's like a trigger, once visited => requested it will trigger a function related to a certain HTTP method ending in a WRRC(web request response cycle.)

3- **When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?**

> **when there are multiple callback functions to handle the method request route, so we add next so each preceding function pass the executive process to the next one untill reaching the last one which doesn't necessirly need a next parameter in it since the functions are done. if you pass a next parameter to a function, you must pass that parameter inside that function but in invoked form ( next() )**

## Express Router

1- **What is an Express Router?**

> An Express Router is a module in Express.js that helps organize and handle routes for HTTP requests.


2- **By what mean do we initialize express.Router() in an express server?**

>const router = express.Router()

3- **What do we use route middleware for?**

>Route middleware in Express is used to perform actions on requests or responses before they are handled by route handlers, such as authentication, logging, validation, error handling

## Reflection

>I am interested in learning more about express.router() and using it in exporting mini apps instead of writing each method and path seperately on a line and never use em again in another application.

## Things I want to know more about

>I would like to learn more in details about classes since we haven't been introduced to it before, and as I believe in will make every process easier since we can use multiple functionalities at once calling out that container (capsule of elements) called a class.
