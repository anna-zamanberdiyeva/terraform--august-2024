Devops API App

install the node packages for the api tier:

→ npm install

start the app

→ npm start

NOTE this app uses two env variables:

PORT: the listening PORT
DB: Name of the database to connect
DBUSER: Database user
DBPASS: DB user password,
DBHOST: Database hostname,
DBPORT: Database server listening port

These variables need to be set





Sample 3tier app
This repo contains code for a Node.js multi-tier application.

The application overview is as follows

web <=> api <=> db
The folders web and api respectively describe how to install and run each app.