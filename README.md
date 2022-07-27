# **Simple User Registration and Login App with MongoDB, ExpressJs, React and NodeJs [MERN]**

![Final App](./demo.gif)
Full-stack MERN app with authentication using passport and JWTs.

###  Made By:
# Sarthak Deore
<br>

## DEMO Link:

- [Click Here](https://xenon-stack-dashboard.herokuapp.com/)

##### This project uses the following technologies:

- [React](https://reactjs.org) and [React Router](https://reacttraining.com/react-router/) for frontend
- [Express](http://expressjs.com/) and [Node](https://nodejs.org/en/) for the backend
- [MongoDB](https://www.mongodb.com/) for the database
- [Redux](https://redux.js.org/basics/usagewithreact) for state management between React components
- [Heroku](https://heroku.com) for deployment


## MongoDB Configuration

Configuration File:  `config/default.json`.
Add the Configuration i.e - Mongo URI in the above file.

```javascript
{
    "mongoURI": "YOUR_MONGO_URI_HERE",
    "secretOrKey": "secret"
}
```
The user schema in mongo is defined in `models/User.js`.

## Features in user API

1. User Registration and Login.
2. Existing User Idenification.
3. Wrong Credentials Identification.
4. Hasing the password before saving into database.
5. Warning during login if email is not registered.


## Quick Start

```javascript
// Install dependencies for server & client
npm install && npm run client-install

// Run client & server with concurrently
npm run dev

// Server runs on http://localhost:5000 and client on http://localhost:3000
```
