# Gestion
ERP system built using MongoDB, Express.js, React, and Node.js, implementing secure RESTful APIs, JWT authentication, role-based authorization, and efficient data management for 500+ simulated users.
Gestion
A College Based Data Management System.

There are two types of roles: Staff[Teacher,HOD] and Student.
Login Details
PS: BE KIND :)

Teacher [staff]
username: Delphine
pwd: Delphine123

Teacher can add or edit

Notes
Attendance
Internal Marks
Time Schedule
HOD (Head of Department) [staff]
username: Moriah
pwd: Moriah123

HOD can do everything Teacher can.
HOD can also

Approve new Teacher
Add New Paper
Student
username: Bret
pwd: Bret

Or register a new Student and Login.
You can also login with the First Name of any student in the class.

Student can view

Notes
Attendance
Internal Marks
Attendance and Marks needs to be added by the teacher first.
Student can also join or leave a Paper(Subject).

Tech Stack
Client: React, TailwindCSS

Server: NodeJS, ExpressJS

Database: MongoDB, Mongoose

Other Features
Profile
Dark Theme
Mobile Responsive
Setting Up
Clone the project:

  git clone https://github.com/gargv837/Gestion.git
Change Directory:

  cd Gestion
Install dependencies:

  npm install
Finally,

  npm start
Using your own server and database
The requests are send to the hosted server by default.
if you want to use your own server and database, follow the steps here to step up one.

Then, go to src/config/api/axios.js. change the baseURL to your backend address:

baseURL: "http://localhost:3500";
baseURL: "https://example.address.com";
RoadMap
Add admin 😴
Cache Queries
Paginate Queries
Contact
Errors are bound to happen and the documentation is incomplete.
I'd love to hear feedbacks and suggestions.
In any case, start a conversation: LinkedIn Mail(Make sure your mail doesn't get flagged as spam/junk)
Thank You ❤️.

Acknowledgements
MERN Stack Tutorial by Dave Gray
React Tutorial by Dave Gray
React Icons
React Router
React Toastify
axios
README Editor
Related
Gestion_api
