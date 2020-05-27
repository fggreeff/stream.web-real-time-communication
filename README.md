# stream.web-real-time-communication

Simple JS service using WebRTC to allow audio and video communication to work inside web pages

## Architecture

The architecture diagram for the application, ensure to seperate current from proposed / target diagrams.

## Getting started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites

A detailed, step by step guide, of the setup of any external dependencies that a service/project may have.

- Chrome 47 or above
- [Web Server for Chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb), or use your own web server of choice.
- [Node](https://nodejs.org/en/download/)
- [Docker](https://www.docker.com/products/docker-desktop)

## Installing

- clone repository

Run App in container:
- `docker-compose up`
- [localhost:8080](http://localhost:8080)

Run App locally:
- `npm install`
- `node index.js`
- [localhost:8080](http://localhost:8080)

## Running the tests

An explanation on how to run any automated tests that relate to the project.

## Deployment

Detail any steps required to deploy the service/project to systems other than the local machine.

## Debug

Take a look at [chrome://webrtc-internals](chrome://webrtc-internals). This provides WebRTC stats and debugging data

## Resources

- [codelabs tutorial](https://codelabs.developers.google.com/codelabs/webrtc-web/#0)
- [webrtc samples](https://webrtc.github.io/samples/)
