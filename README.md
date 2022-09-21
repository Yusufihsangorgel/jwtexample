# jwtexample
jwt auth example with nodejs-expressjs-mongodb

<br />

## Manual Installation

- clone this project
- npm install
- Create .env file --> example : 
API_PORT= Your port here

MONGO_URI= Your database URI here

TOKEN_KEY = token key here

- npm start

<br />

<br />

## Example Register Post Request with Postman 

Url : http://localhost:YOURPORT/register

{
	"first_name":"firstname",
	"last_name":"lastname",
	"email": "exampleemail@gmail.com",
    "password" : "12345"
}

<br />

<br />

## Example Login Post Request with Postman 

Url : http://localhost:YOURPORT/login

{
	  "email": "exampleemail@gmail.com",
    "password" : "12345"
}

<br />

<br />

## Example Welcome Get Request with Postman (if user already logged)


Url : http://localhost:YOURPORT/welcome

Go to Headers and add this :

x-access-token       your-user-token

<br />
