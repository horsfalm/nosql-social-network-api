# nosql-social-network-api

 ## Table of Contents:  
[1. Description](#Description)  
[2. Acceptance Criteria](#Acceptance-Criteria)  
[3. Demonstration Video](#Demonstration-Video)  
[4. Tests](#Tests)  
[5. License Details](#License-Details)  
[6. Repository](#Repo)   
[7. Follow-up](#Follow-up)  

## Description:
The project involves a number of API calls for an undeployed (no front-end) social network using Express.js, MongoDB database / Mongoose ODM, and is dependent on Moment.js for time stamp formatting.

## Acceptance Criteria:

GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list

## Demonstration Video
[Video #1 of 2](https://vimeo.com/manage/videos/687538487)  
[Video #2 of 2](https://vimeo.com/manage/videos/687538896)  

## Tests:  

API tests have been tested through Insomnia

USER ROUTES
===========
GET and POST
http://localhost:3001/api/users
GET, PUT and DELETE
http://localhost:3001/api/users/:id

THOUGHT ROUTES
==============
GET AND POST
http://localhost:3001/api/thoughts
GET, PUT and DELETE
http://localhost:3001/api/thoughts/:id

FRIEND ROUTES
=============
POST and DELETE
http://localhost:3001/api/users/:id/friends/:id

REACTION ROUTES
===============
POST
http://localhost:3001/api/thoughts/:id/reactions
DELETE
http://localhost:3001/api/thoughts/:id/reactions/:id

## License Details: 
ISC license  

## Repository:
 [Github repository](https://github.com/horsfalm/nosql-social-network-api)

## Follow-up:
GitHub: https://github.com/horsfalm  
Email: horsfalm@gmail.com