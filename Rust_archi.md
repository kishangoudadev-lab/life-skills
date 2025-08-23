# REST Architecture

REST (Representational State Transfer) is a software architectural style for designing networked applications. It allows communication between a client and a server over HTTP using stateless interactions. The resources (data or services) are identified by URLs (or more precisely, URIs), which are manipulated by basic HTTP methods.

## Key Principles
* **Statelessness**: Each request from the client contains all the information needed to process it. The server does not store any session state between request.
* **Client-Server**: The client handles the user interface, and the server manages resources.
* **Uniform Interface**: Communication happens through standard methods (HTTP verbs).
* **Cacheable**: Responses can be cached to improve performance.
* **Layered System**: Components can be organized in layers for better scalability and security.
* **Resource-Based**: Everything is treated as a resource, identified by a unique URL.

## Example
If are the user you can perform following :-
* `GET /users` → Get all users  
* `GET /users/1` → Get user with ID 1  
* `POST /users` → Create a new user  
* `PUT /users/1` → Update user with ID 1  
* `DELETE /users/1` → Delete user with ID 1  

## Advantages
* Easy to understand and use
* Scales well across different platforms
* Uses standard HTTP, no extra tools needed
* Flexible and language-independent

## References
* https://restfulapi.net/
* https://www.redhat.com/en/topics/api/what-is-a-rest-api
* https://www.youtube.com/watch?v=lsMQRaeKNDk
