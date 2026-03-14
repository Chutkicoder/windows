npm init -y
npm install express mongoose
node server.js
now download thunder client extension
then you will see just below the extension a thunder icon (on the side bars)
click on the thunder icon then 
click on new request
after that post
then give http://localhost:3000/students this link
click body
{
 "name": "Shreya",
 "age": 21,
 "course": "BSc IT"
} inside body this.
then send 
after that open it on browser and see http://localhost:3000/students
mostly the o/p: is just besides the body you will get the response
POST

http://localhost:3000/students

Body (JSON)

{
 "name": "Shreya",
 "age": 21,
 "course": "BSc IT"
}
Read Students

GET

http://localhost:3000/students
Update Student

PUT

http://localhost:3000/students/{id}
{real id} copy it from response then put it on the link and update age as 22.

Example body:

{
 "age": 22
}
Delete Student

DELETE

http://localhost:3000/students/{id}