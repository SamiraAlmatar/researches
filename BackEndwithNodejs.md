 # Back-End with [Node.js](https://nodejs.org/en/).

### what is the [Back-end](https://www.codecademy.com/articles/back-end-architecture):
The back-end is the code that runs on the server, that receives requests from the clients, and contains the logic to send the appropriate data back to the client using [HTTP](#http). The back-end also includes the database, which will persistently store all of the data for the application.


![](http://www.dailywebsolutions.com/images/client-server-architecture.png)

**Node.js** use [Express](#express) frameworks to develop back-end application

## [Express](http://expressjs.com/) 

Express is one of the most widely-used frameworks for Node.js. It simplifies base features of Node.js, making it easier and faster to build your application's backend. Learning Express gives you a great foundation for becoming a Node.js developer.

Express is a routing and middleware web framework that has minimal functionality of its own: An Express application is essentially a series of middleware function calls.

[Middleware](http://expressjs.com/en/guide/using-middleware.html) functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle. The next middleware function is commonly denoted by a variable named next.


## [HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)

**Hypertext Transfer Protocol** is an application-layer protocol for transmitting hypermedia documents, such as HTML. It was designed for communication between web browsers (client) and web servers ( server).

HTTP is a [stateless](https://en.wikipedia.org/wiki/Stateless_protocol) protocol, meaning that the server does not keep any data (state) between two requests.

Each individual request is sent to a server, which will handle it and provide an answer, called the response. Between this request and response there are numerous entities
### HOW IT WORKS

  ###### MAKING REQUESTS
  client make a request to the server in order to retrieve or modify data on the server. 
  Requests consists of the following elements:

  * [HTTP verb](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods), which defines what kind of operation to perform
  	 > There are 4 basic HTTP verbs we use in requests (Get, Post, Put, Delete) 
  * Path to a resource
  * The version of the HTTP protocol.
  * [Header](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers), which allows the client to pass along information about the request
  
  * Optionally,a body containing data
  
  
 ###### SENDING RESPONSES
 
 the server is sending a data payload to the client, the server must include a content-type in the header of the response. This content-type header field alerts the client to the type of data it is sending in the response body. These content types are MIME Types,`Multipurpose Internet Mail Extensions. It's a way of identifying files on the Internet according to their nature and format`. just as they are in the accept field of the request header. The content-type that the server sends back in the response should be one of the options that the client specified in the accept field of the request.
 
 Responses consist of the following elements:
 
 * The version of the HTTP protocol 
 * A [status code](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status), indicating if the request has been successful, or not, and why.
 * A status message, a non-authoritative short description of the status code.
 * HTTP [headers](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers), like those for requests.
 * Optionally, a body containing the fetched resource.
 
 ![](http://sasi-kala.com/assets/posts_img/9_HTTP_Message_Format.jpg)
 
 **REQUEST**

![](https://mdn.mozillademos.org/files/13687/HTTP_Request.png)
**RESPONSE**
![](https://mdn.mozillademos.org/files/13691/HTTP_Response.png)


## Resources
* [http://expressjs.com/en/guide/using-middleware.html](http://expressjs.com/en/guide/using-middleware.html)
* [https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)
* [https://www.codecademy.com/articles/what-is-rest](https://www.codecademy.com/articles/what-is-rest)
* [https://www.codecademy.com/articles/back-end-architecture](https://www.codecademy.com/articles/back-end-architecture)
* [https://codeyourfuture.github.io/syllabus-master/node-db/week-13/lesson.html](https://codeyourfuture.github.io/syllabus-master/node-db/week-13/lesson.html)