# AlmaBetter Backend Project 

## Get_Youtube_Subscribers
This is a simple backend project that contains a RESTful API for getting information about YouTube channel subscribers. The project is developed with Node.js and Express, and the database used for managing the subscriber data is MongoDB. The subscriber's data consists of fields such as their ID, Names, Subscribed Channels, and Subscription Date.

The API has several endpoints that let users get data in JSON format, such as an endpoint that returns a list of all subscribers, an endpoint that returns a list of names and subscribed channels for each subscriber, and an endpoint that returns information about a subscriber based on their ID.

## API Endpoints 
1. **"/ "** -> This default route will render the "index.html file" when the app launches. http://localhost:4001/

![Screenshot 2023-06-24 214215](httpsb10)
2. **"/subscribers "** -> This endpoint returns an array of all subscribers in the database. http://localhost:4001/subscribers

![248499126-ef0e992e-621b-4dce-a452-3eaf5cc38271](https://github.com/Reflaxtion/Youtube-Subscribers/assets/126673677/27928526-e56d-459b-9914-3382c94ea2d8)
3. **"/subscribers/names "** -> This endpoint returns an array of subscribers with only two fields, their name and subscribed channel. http://localhost:4001/subscribers/names

![248499112-c18e2d44-8a81-4b63-a130-9cd7ff67fd64](https://github.com/Reflaxtion/Youtube-Subscribers/assets/126673677/31a5c90b-475e-4166-b001-473c10ac947b)
4. **"/subscribers/:id "** -> This returns the details of subscriber whose Id is provided in endpoint. http://localhost:4000/subscribers/:id

![248499105-899f4536-7a7d-4857-8d98-298350e860f0](https://github.com/Reflaxtion/Youtube-Subscribers/assets/126673677/0c391dfb-b956-4536-94a5-a8365254d659)
## Application Folder Structure
1. [src/app.js] -> For handling requests and responses.

2. [/index.js] -> To connect and start the server.

3. [src/createDatabase.js] -> To create database on MongoDB.

4. [src/data.js] -> Data that has to be connnected to a database.

5. [src/models/subscribers.js] -> For the schema.
   
6. [src/index.html] -> The home page for the application.
```
├── src/
│   ├── app.js
│   ├── createDatabase.js
│   ├── data.js
│   ├── index.html 
│   └── models/
│       ├── subscribers.js
├── index.js   
├── {} package-lock.json
└── {}package.json
```

## Installation 

You'll need to have **Node.js** and **MongoDB** installed on your computer in order to begin working on the project. 

Once installed, Clone this repository to your **local** machine.

Install the required dependencies as mentioned below by using **npm install <packageName>**.

Start the server by **nodemon index.js**

## Dependencies
Following dependencie are needed to run this application: 

1. express

2. mongoose

3. nodemon

## Deployment

Visit to see the working on Youtube : 

Web Deployment :  

## Team Memebers

- Chandan kumar
- Lokendra kumar



