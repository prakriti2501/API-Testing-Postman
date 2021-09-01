# API-Testing-Postman
TASK 1:  API testing via Postman and automating via Python
This repo includes the task in which I used postman to send a GET request to the API (https://www.flickr.com/services/api/flickr.photos.getPopular.html).
We have sent a GET Request via HTTP protocol to the Flicker API and got the response in JSON format using Postman.

# POSTMAN
Postman is a tool to interact with web-based APIs.
# HTTP Call and JSON Response
In our communication between the client and the server, the client is Postman and the server is the the given Flicker API, we are using HTTP messages. 

*The Hypertext Transfer Protocol (HTTP) is designed to enable communications between clients and servers.
 HTTP works as a request-response protocol between a client and server.
 The two most common HTTP methods are: GET and POST. {We have used the GET method.}
 GET is used to request data from a specified resource.

The HTTP message which goes from client(Postman) to Server (Flicker API) is called a REQUEST and what is coming back is called the RESPONSE.

# Most important failure points in the response
When an API request fails due to request errors or server errors, an error response message is returned in JSON format.
For Example: 
->API request attempts to get information about a non-existent reference set
->The resource is available and not modified.
-> The requested resource does not support one or more of the given parameters.


# If I were to automate this API’s response testing as a Flickr employee, the criteria I would choose as the success/fail validation would have been:
->Status 200OK 



I am attaching the screen recorded session explaining the same.
Thanks You!
