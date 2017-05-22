# WolfBeacon Core API

The Core WolfBeacon API for authenticated mobile and web clients providing primary organisational and retrieval services.

Powered by [Node](https://nodejs.org/en/)/[Express](https://expressjs.com/)/[Mongoose](http://mongoosejs.com/), authentication by [Auth0](https://auth0.com), transpiled by [Babel](https://babeljs.io) and Documentation generated by [ApiDoc](http://apidocjs.com/).

## API Documentation

Find the documentation at [https://wolfbeacon.com/api/docs](https://wolfbeacon.com/api/core/docs)

## Local Setup:

#### Dependencies: [npm](https://www.npmjs.com/)

* `npm install`
* Create the .env file and enter the `MONGODB_URI`
* `npm start`
* Alternatively, to use nodemon, install it using `npm install -g nodemon` and run as `npm test`

## Running/Deploying with [Docker](https://docs.docker.com/engine/installation/)
* `docker service start #sudo`
* `docker build -t wolfbeacon-core-api . #sudo`
* `docker run docker run wolfbeacon-core-api #sudo`
