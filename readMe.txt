This folder is to create an express api

ReadMe on how to start this project.

1. create folder: mkdir track-server
2. create package json: mpn init -y
3. install independencies: npm install bcrypt express jsonwebtoken mongoose nodemon

Creating A mongo DB instance,

1. go to website, and create a new cluster (Standard Login)
2. select free teir for yoru cloud data base
3. in configuration you will need to white list your current ip address.
    3a. this project was initated on a work wi-fi, this will need to be changed in order to work from other internet connections
4. choose connection method, i this case i selected a connection string
5. once everything is set up use: npm run dev : to run nodemon