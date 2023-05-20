
## Overview
_________
🚀 this project
is a perfect to the concepts of server-side web development. You’ll learn the different parts that make up the back-end of a website or web application, and you’ll gain familiarity with the Node.js runtime environment. After this course, you’ll be set up to explore popular Node frameworks like Express.js to build great API's.<br>

🚀 You learn in this project how to use mongoDb without any installing extra tools, MongoDB is now on cloud, so you will store your database in safe place!<br>

🚀 Using ngrok to test APIs<br><br>
## Installation and usage
____


Be sure, you have installed all dependencies and applications to run React Native project on your computer : [Getting Started with Node.js](https://nodejs.org/en/docs).<br>

This project works fine for iOS but in Android version there are serious UI problems because I've only worked on iOS.<br>
### Running the project
Clone this repository :<br>

<code>https://github.com/markure-oss/API-Food-Store-App.git </code>
<br>

Install packages :<br>

<code>npm install</code>
<br>

When installation is complete, run with version of your choice :
<code>npm start</code>

## Setup MongoDB
____
1.Configure MongoDB Atlas, [follow the instructions](mongodb.com/cloud/atlas/register)<br>

2.When connect, you can use multiple options from MongoDB. But you should connect your application<br>

⚠️ it looks like this:<br>

![](public/uploads/mongo.png)<br>

3.replace this connection string into the variable <code>CONNECTION_STRING</code> in the file <code>.evn</code>

## Deploy your App to Global in NgRok
____
Download Ngrok 
<code>https://ngrok.com/download </code>

Start a tunnel:
<code>ngrok http 8080</code>
