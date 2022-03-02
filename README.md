# cloudesign
mearn/stack
# mearn-Stack
MEAN / MERN Stack Assignment
# Getting Started with Create React App


MEAN / MERN Stack Assignment

in backend first ........npm i module
in frontend first........rm -rf node_modules
................npm install


Create a form to save task in database
.by using front end we  fill the data in the form and its goes to the db.
     ....front end  = npm start.       
            port= 3000     

     ....backend= nodemon index.js
            port 5000

rest edit part update and delete done with the help of post man by using apis
        ........getDetails API= ocalhost:5000/getDetails
         .......update API=   localhost:5000/update/form Id
         ......delete API= localhost:5000/delete/formId

         ##Note= I am unable to do edit currently by using fronend thats why i am doing this edit part withe the help of only backend.....by using postman.



Create components to create & edit task
TASK Schema
o Title (text)
o Description (text)
o Status (ENUM [Open, In-Progress, Completed])
o Datetime stamp (timestamp)
RESTful API to create and edit task.
Integrate the frontend and backend.
