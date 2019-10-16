# Assignment 0
First assignment that combines some Git and Linux commands with Docker concepts. 

This repository is a simple node.js application built and tested using **node version 8.10.0** and **npm version 3.5.2**. The task is to turn this node.js application into its own docker container.

You may use a [nodejs docker image](https://hub.docker.com/_/node/) as your base image in your Dockerfile. Make sure to select the correct version. See the section on running the application for how to start a node app. 

## The Task 
Create and run a Docker container that encapsuslates this application. Additionally, write a linux script that "tests" the application is working correctly based on the steps outlined in the Testing the application section. 

## Running the application
This section outlines steps to run this application and assumes you have a working nodejs environment that you can use. 
1. Run `npm install` to install the dependency packages. 
2. Run `npm start` to start the application. This will start a webserver that will **listen on port 3000**. 

## Testing the application
To test if the application is working correctly, navigate to http://localhost:3000 in your browser. Your browser should display **Hello World!** if the application is functioning correctly. 
