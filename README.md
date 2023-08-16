# BookMyShow API
This project is powered by NodeJS with express to build APIs for a movie booking application named BookMyShow. 

We have exposed two endpoints as per the requirements of the project:

**/api/booking** **:method:GET** : Will retrieve the last booking details from the MongoDB BookMyShow collection and send it to the client with 200 status code

**/api/booking** **:method:POST** : Will create a booking document  in the MongoDB collection after schema validation and send 200 status to the client for success and 400 status code incase of error 

 

 ## directory💠
    We have split the schema, the app and the routes into different modules
 - **/src/app**- Contains the code for mongoDB atlas connection and  express app spawning
 - **/src/Models**- Contains the Schema.js file which holds the schema for the Booking object for mongoDB
- **/src/Routest**- Contains the Routes.js file which holds the code to the API endpoint routes


## Reflection💠

- This project gave me a beautiful insight about the intricacies involved with backend the communication process with the front-end, learnt many other things along the way like JWT authentication and authorization(not implemented in this project).

## Built with

<a href='https://nodejs.org/en' ><img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white"  height="25"></a>
<a href='https://expressjs.com/' ><img src="https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB"  height="25"></a>
<a href='https://www.mongodb.com/' ><img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white"  height="25"></a>


## Deployed on
<a href='https://render.com/' ><img src="https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white"  height="25"></a>
