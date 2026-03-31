# AMA Questions

## How to select all `<p>` elements using DOM?
You can select all `<p>` elements using document.querySelectorAll():
const paragraphs = document.querySelectorAll("p");
This returns all `<p>` elements as a NodeList.

## What is an HTTP Header?
An HTTP header is information sent between the client and the server. It contains metadata about the request or response. Request headers are sent by the browser, and response headers are sent by the server.

## What is a Server?
A server is a system that provides data or services to other computers (clients) over a network. For example, a web server sends web pages to your browser.

## How to convert object to JSON and vice-versa?
To convert an object to JSON, use JSON.stringify():
const obj = { name: "John", age: 25 };
const json = JSON.stringify(obj);

To convert JSON back to an object, use JSON.parse():
const parsedObj = JSON.parse(json);

## Difference between Synchronous and Asynchronous?
Synchronous code runs line by line and blocks execution until the task is completed. Asynchronous code does not block execution and allows other tasks to run while waiting, using callbacks, promises, or async/await.

## Async or Sync, which will be scheduled?
Asynchronous tasks are scheduled. They are handled by the event loop and executed later. Synchronous code runs immediately.

## What is Node.js?
Node.js is a runtime environment that allows you to run JavaScript outside the browser. It is built on Chrome's V8 engine and is mainly used for backend development.

## What is a Status Code?
A status code is a 3-digit number sent by the server to indicate the result of a request. For example, 200 means success, 404 means not found, and 500 means server error.

## What is Status 200?
Status code 200 means the request was successful and the server has returned the requested data. Example: HTTP/1.1 200 OK
