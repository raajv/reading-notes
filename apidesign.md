What does REST stand for?
In 2000, Roy Fielding proposed Representational State Transfer (REST) as an architectural approach to designing web services. REST is an architectural style for building distributed systems based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP. However, most common REST API implementations use HTTP as the application protocol, and this guide focuses on designing REST APIs for HTTP.


REST APIs are designed around a resource.

What is an identifer of a resource? Give an example.

A resource has an identifier, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:

HTTP

Copy
https://adventure-works.com/orders/1


What are the most common HTTP verbs?

GET, POST, PUT, PATCH, and DELETE.

What should the URIs be based on?

When possible, resource URIs should be based on nouns (the resource) and not verbs (the operations on the resource).

Give an example of a good URI.

https://adventure-works.com/orders
What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

 Avoid "chatty" web APIs that expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires.


What status code does a successful GET request return?

code 200
What status code does an unsuccessful GET request return?

return 404 (Not Found).
What status code does a successful POST request return?

If a POST method creates a new resource, it returns HTTP status code 201 (Created).
What status code does a successful DELETE request return?

If the delete operation is successful, the web server should respond with HTTP status code 204 (No Content),

- ref https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design