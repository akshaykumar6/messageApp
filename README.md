# Message App

Sample web application to understand 12 factor app principles using docker.

## Routes exposed

HTTP verb | URI | Action
----------| --- | ------
GET | /message | list all messages
GET | /message/ID | get message with ID
POST | /message | create a new message
PUT | /message/ID | modify message with ID
DELETE | /message/ID | delete message with ID

## Setup

* Install dependencies: `npm install`
* Launch the application: `sails lift`

## Links

- [12 factor app lab by Docker](https://github.com/docker/labs/tree/master/12factor)
- [The Twelve Factors](https://12factor.net/)

