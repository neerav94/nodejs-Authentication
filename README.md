# nodejs-Authentication

Implemented user registration and authentication in nodejs using passport. Database used is mySql

Usage:
npm install
npm start

Endpoints:
POST: /users/register
POST: /users/authenticate //Gives back a token
POST: /users/profile //needs json web token to authorize
