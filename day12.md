# CRUD

### In your own words, describe what each group of status code represents

- 100’s = Informational status codes, these are used to inform the client that the request was received and understood.
- 200’s = Success codes, these are used to inform the client that the request was successfully received, understood, and accepted.
- 300’s = Redirection codes, these are used to inform the client that the resource they are requesting isn’t available at the expected location anymore.
- 400’s = Client error codes, these are used to inform the client that there was a problem with their request.
- 500’s = Server error codes, these are used to inform the client that there was a problem with the server.


### What is a status code 202? 
this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending.

### What is a status code 308?
This tells the client to use another URL to access the resource and not use the current URL anymore

### What code would you use if an update didn’t return data to a client?
204

### What code would you use if a resource used to exist but no longer does?
410 Gone

### What is the ‘Forbidden’ status code?
403 , The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource

### Why do we need to pull our MongoDB database string out of our server and put it into our .env?

So that we can hide our database string from the public.

### What is middleware?

Middleware is software that provides common services and capabilities to applications outside of what’s offered by the operating system.

### What does app.use(express.json()) do?

This is a built-in middleware function in Express. It parses incoming requests with JSON payloads and is based on body-parser.

### What does the /:id mean in a route?

This is a parameter, it is used to capture the value of whatever we specify after the “/”.

### What is the difference beween PUT and PATCH?

PUT is used to update a resource, and PATCH is used to modify a resource.

### What does a 500 error status code mean?
Internal Server Error
### What is the difference between a status 200 and a status 201?

- 200 OK, this code tells the client that the request has succeeded.
- 201 Created, this code tells the client that the request has succeeded and has led to the creation of a new resource.


