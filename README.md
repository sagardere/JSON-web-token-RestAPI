# Node.js-RESTful-APIs-with-JSON-Web-Tokens
Authentication of HTTP requests using JWT tokens in your Node.js applications. 

How to secure a Nodejs RESTful CRUD API using JSON web tokens?

This tutorial will demo how to use JWT with an existing bare bones 
API using mongodb as the database.

It consist of a User model and controller. The model
defines the data, and the controller will contain all 
the business logic needed to interact with the database. 

It has a db file which will be used to
connect the app to the database, and an app file used
for bootstrapping the application itself.

The server file is used to spin up the server and tells the
app to listen on a specific port.

The auth folder contains the configuration for registering and 
logging users in, signing and verifying tokens.

