# What are API's?
APIs are sets of tools that help software components talk to each other. They make it easier for developers to access features and services from other software without having to understand how it works. APIs are popular because they save time and effort, and allow for more efficient software development.  For example, a developer building a mobile app that needs to display weather information might use an API provided by a weather service to get the data they need.

![End User with Browser](https://user-images.githubusercontent.com/129942042/230396656-cbcee920-2f7f-42a7-b994-81b325d0aaec.png)



## - What is a REST API? What makes an API RESTful?

A REST API is a type of API that follows a set of principles called **Representational State Transfer (REST)***. A RESTful API follows these principles, which include using a standardised set of methods to access and manipulate resources, identifying each resource with a unique URL, and providing links to related resources in the response.

## - What is HTTP? (what does it stand for and what is it used for?)

HTTP stands for Hypertext Transfer Protocol. It is a protocol that defines how data is transmitted between web servers and clients, such as web browsers. HTTP is used for requesting and transmitting information across the internet. When a user enters a URL into their web browser, HTTP requests the content from the web server, which sends an HTTP response containing the requested content.

## - How is an HTTP request structured?

An HTTP request consists of three parts: the request line, headers, and the message body:

Request Line: The first line of an HTTP request contains the request method, the requested URL, and the HTTP version.

Headers: Headers contain additional information about the request, such as the user agent, content type, and authentication information.

Message Body (Optional): The message body contains any additional data that needs to be sent with the request, such as form data or file uploads. This part is optional and is not present in all requests.
![HTTP_request](https://user-images.githubusercontent.com/129942042/230397769-a9f781d4-0e45-4c27-b08c-7e298ba65716.png)

## - And how is as HTTP response structured?

An HTTP response also consists of three parts: the status line, headers, and the message body.

Status Line: The first line of an HTTP response contains the HTTP version, status code, and status message.

Headers: Headers contain additional information about the response, such as content type, cache-control, and cookies.

Message Body: The message body contains the requested resource or any additional data that needs to be sent with the response, such as error messages or HTML content.

![StructureOfAHTTPResponse-660x374](https://user-images.githubusercontent.com/129942042/230399489-ef6f41ce-8ca7-422d-bad0-ed1d5865943e.png)

## - What is an HTTP verb and what to the 5 main ones do?

An HTTP verb is a type of request that a client can make to a server using the HTTP protocol. It defines the type of action to be performed on a resource identified by a URL, such as retrieving data or submitting new data to the server. The main ones are:

**GET**: Used to retrieve data from a specified resource. When you type a URL into a web browser, a GET request is sent to the server to retrieve the resource located at that URL. GET requests are usually used to retrieve data, but they do not change the state of the resource on the server.

**POST**: Used to submit data to be processed to a specified resource. POST requests are commonly used to send form data to the server. POST requests can create new resources on the server or update existing ones.

**PUT**: Used to update a specified resource with new data. PUT requests replace the entire resource with the new data provided in the request.

**PATCH**: Used to update a specified resource with new data. PATCH requests are similar to PUT requests, but they only update a portion of the resource instead of replacing the entire resource.

DELETE: Used to delete a specified resource. DELETE requests delete the resource at the specified URL from the server.

## - What is "statelessness"

Statelessness is a design principle in which a system or protocol does not store any information or state about previous interactions between the end user and the server. In the context of web development, it means that each HTTP request sent from an end user to a server contains all the necessary information to complete the request, without relying on any previous requests or sessions. This approach makes web applications more scalable and easier to maintain, but it also requires more careful design to ensure that all required information is included in each request.


## - What is caching?

Caching is the process of storing frequently accessed data in a temporary storage area called a cache. When a user requests a web page or other data, the server first checks if the data is already stored in the cache. If it is, the server returns the data from the cache instead of generating it again, which can result in faster response times and reduced server load. 

## - What is Postman?

Postman is an API platform for building and using APIs. Postman simplifies each step of the API lifecycle and streamlines collaboration so you can create better APIs—faster. Allows developers to design, test, and document APIs. It provides a user-friendly interface for creating and sending HTTP requests to a server and receiving responses, making it easier to test and debug APIs during the development process. Postman also includes features such as automated testing, mock servers, and team collaboration tools to streamline the API development workflow.
