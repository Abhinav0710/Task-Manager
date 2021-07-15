# Task-Manager
This is a development version of Task App (worked on this as guided by the nodejs course instructor Andrew Mead) which enables the user to create profile(add an image(avatar) for your profile too!) and keep a track of the tasks to be performed/already performed.


# Set up database
To start a new database instance run the following command
{path-to-mongod-file} --dbpath={path-to-data-storage}
/"Program Files"/MongoDb/Server/3.2/bin/mongod.exe -dbpath=/data/db
* The connection URL would be: mongodb://127.0.0.1:27017

# Advanced Postman Summary
* Enviroment variables can be created to store data that is going to be used in all requests. This can be done by creating an environment (dev or prod) and then creating environment variables with key value pairs. Then variables can be used using the following syntax: `{{env_variable_name}}``

* Authorization can be added to all requests in a collection, by setting the authotization type in the Authorization tab for each request (default value is to be inherited for parent). Therefore, the authorization token must be defined for the whole collection. This can be done by selecting the collection options and then selecting Edit. The same options should appear but when a change is made it applies to all the requests.

* The authorization token can also be defined as an environment variable

* Pre-requisite scripts could be defined to run Javascript code before the request is sent. The same happens for the Tests tab, however this code is ran after sending the request.

# Features
* Create a user account
* Create, edit and delete tasks
* Filter your tasks by completion
* Sort tasks by date
* Decide how many tasks you want to see
* Update your account information
* Delete the user

# Tech Stack
* Node.js
* Express
* MongoDb
* JWT for authenticaion

