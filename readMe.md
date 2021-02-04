## About the Application 

This is the back end server for Fit-bitter.

This folder is to create an express api and make calls to a mongodb database that 
stores users of the application and their track records.

## Technologies Used

  * Node.js
  * Express
  * MongoDB
  * mongoose

## API's Used

  * Google Maps 

## How to run this application

1. create folder: mkdir track-server
2. create package json: mpn init -y
3. install independencies: npm install bcrypt express jsonwebtoken mongoose nodemon

# Creating A mongo DB instance

1. Go to website, and create a new cluster (Standard Login).
2. Select free teir for yoru cloud data base.
3. In configuration you will need to white list your current ip address.
    3a. This project was initated on a work wi-fi, this will need to be changed in order to work from other internet connections.
4. Choose connection method, in this case I selected a connection string.
5. Once everything is set up use: npm run dev : to run nodemon.
