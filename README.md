# nodejs-Authentication

API for registering users with MySQL and authentication using JWT (Jason Web Token). This app uses passport and passport-jwt and uses a JWT strategy 

Usage:
npm install
npm start

Endpoints:
POST: /users/register

POST: /users/authenticate //Gives back a token

POST: /users/profile //needs json web token to authorize
