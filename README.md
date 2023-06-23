# Pococare_assignment

A Doctor's Appointment Booking System - lets you Register and Login and be able to view Doctors, book appointment, view/reschedule, delete appointments and receive mail once appointment is confirmed.


## Tools used:
[![My Skills](https://skillicons.dev/icons?i=vercel,github)](https://skillicons.dev)
<img alt="Coder GIF" height=50 width=80 src="https://www.w3schools.com/whatis/img_npm.jpg" />


## Tech Stacks used:
[![My Skills](https://skillicons.dev/icons?i=js,nodejs,express,mongodb,html,css)](https://skillicons.dev)


# Live Demo Link [https://kmch.netlify.app/](https://kmch.netlify.app/)

# Backend deployed using RENDER https://pocobackend.onrender.com/

# Home Page
![image](https://github.com/rajesh1028/pococareAssignment/frontend/images/assets/indexpage)

# Click on Sign Up to Register
![image](https://github.com/rajesh1028/pococareAssignment/frontend/images/assets/indexpage)

# Click on Login to signin
![image](https://github.com/rajesh1028/pococareAssignment/frontend/images/assets/indexpage)


 You can also click For VIDEO CONSULTATION which will redirect to another page which is a ROOM where Patient and Doctor can have a meet via Video**


# How To:

If you wish to run this project on your local machine

Follow the given steps:

* Clone our repository https://github.com/rajesh1028/pococareAssignment.git

* Open our code in VS code

* Then do npm install to require the necessary packages and dependencies

* Go to Backend folder - cd backend

* do npm run server

* Congrats! you have successfully started the application.

## API end points

api - https://pococare1.onrender.com/


| METHOD | ENDPOINT | DESCRIPTION | STATUS CODE |
| --- | --- | --- | --- |
| POST | api/patients/signup | This endpoint allow Patients to register. | 201 |
| POST | api/patients/login | This endpoint allow Patients to login. | 201 |
| PATCH | api/patients/update/:id | To update user
| DELETE | api/patients/delete/:id | To delete user
| GET | api/patients/all | To get all users | 200
| POST | api/patients/logout | To log user out
| POST | api/doctors/signup | This endpoint allow Doctors to register. | 201 |
| POST | api/doctors/login | This endpoint allow Doctors to login. | 201 |
| PATCH | api/doctors/update/:id | To update user
| DELETE | api/doctors/delete/:id | To delete user
| GET | api/doctors/all | To get all users | 200
| POST | api/doctors/logout | To log user out
| GET | api/appointments/ | To get all appointments | 200
| POST | api/appointments/add | This endpoint allow patients to add appointment. | 201 |
| PATCH | api/appointments/update/:id | To update appointment
| DELETE | api/appointments/delete/:id | To delete appointment
| GET | api/appointments/docapp/:id | To get the appointments based on specific Doctor | 200
| GET | api/appointments/patapp/:id | To get the appointments based on specific Patient | 200






# Thanks for your time, have a nice day!!!!



