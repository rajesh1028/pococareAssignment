# Pococare_assignment

### User Account: rajeshkaruppusamy@gmail.com
### Password    : rajesh

### Doctor Account: doctor@gmail.com
### Password      : doctor

A Doctor's Appointment Booking System - lets you Register and Login and be able to view Doctors, book appointment, view/reschedule, delete appointments and receive mail once appointment is confirmed.


## Tools used:
[![My Skills](https://skillicons.dev/icons?i=vercel,github)](https://skillicons.dev)
<img alt="Coder GIF" height=50 width=80 src="https://www.w3schools.com/whatis/img_npm.jpg" />


## Tech Stacks used:
[![My Skills](https://skillicons.dev/icons?i=js,nodejs,express,mongodb,html,css)](https://skillicons.dev)


# Live Demo Link [https://kmch.netlify.app/](https://kmch.netlify.app/)

# Backend deployed using RENDER https://pocobackend.onrender.com/


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
| POST | api/user/signup | This endpoint allow Patients to register. | 201 |
| POST | api/user/login | This endpoint allow Patients to login. | 201 |
| PATCH | api/user/update | To update user password
| GET | api/user/ | To get all users | 200
| POST | api/doctor/signup | This endpoint allow Doctors to register. | 201 |
| POST | api/doctor/login | This endpoint allow Doctors to login. | 201 |
| PATCH | api/doctor/update | To update doctors password
| GET | api/doctor/ | To get all doctors | 200
| GET | api/doctor/slots/ | To get all appointments | 200
| POST | api/doctor/addSlot | This endpoint allow patients to add appointment. | 201 |
| PATCH | api/doctor/updateSlot | To update appointment
| POST | api/email | To send email to the user
| GET | api/videocall | To make video call






# Thanks for your time, have a nice day!!!!



