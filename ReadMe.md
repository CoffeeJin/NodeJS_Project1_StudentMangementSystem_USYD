# Summary
This is a group project and I was the head programmer and team leader.

The project is done by NodeJS, React, Express, PostgreSQL, Docker, nginx.

This project aims to develop a student management system.

The user should be able to view, add, edit the studnet information.

A simple deeployment video could be found by: https://www.youtube.com/watch?v=md_Qt3EHspQ

A simple feature introduction could be found by: https://www.youtube.com/watch?v=kxElqAA5Vfg

## Project Title
Canvas Integration Tools for Schools
## Group Name
CP2B/SOFT3888 2021 S2 tutorial 4 group 5
## Group Members
Jin 480546614  
Chloe 470261488  
Jacky 470030688  
Caleb 490161470  
Will 490028302  
## Description
This project is a middle-layer management interface that is able to customize and configure the setup of Canvas for course and students management.  
The application is developped as the Capstone project of SOFT3888 2021 S2 tutorial 4 group 5 in 2021 S2.  
Cian Byrne plays the client to determine requirements.  
Jinxuan Yang plays project manager.  
Please contact jyan2937@uni.sydney.edu.au for any issues.
## Development environment
Node v12.16.1  
PostgreSQL 11
# How to Launch
## Launch in IDE
The application is a NodeJS application  
To launch the project:  
1. Change the config of the database. Before the delivery, we run this application on Cloud server and the server will be closed on December 30, 2021.  
   The path of config file is /project/server/config/default.json, please make sure the name of the config file is default.json.  
   The sql query could be found in /project/server/database.sql.  
2. Start front-end  
   To start the front-end application, you need to run 'npm install' firstly in the console at the path /project/client.  
   After the install finished, run 'npm start' to launch the React application.  
   Once the application luanches successfully, you can access it via browser (Google Chrome suggest!) at http://localhost:3000/.
3. Start back-end
   To start the back-end application, you need to run 'npm install' firstly in the console at the path /project/server.  
   After the install finished, run 'npm start' to launch the Express application.  
## Launch in Docker
We provide a easier way to try our application by Docker.  
You need to install Docker via https://www.docker.com/get-started and version 20.10.8 suggested  
Once the docker install, please open console and move to /project with comman 'docker-compose up' to launch the application.  
The first time launch will take more time to install docker environment.  
Cloud server will be provided until December 30, 2021. You can edit the server via /project/server/config/default.json as well.
Once the launch process successfully, you can access it via browser (Google Chrome suggest!) at http://localhost:3050/.
## Test
The test process is only ready in IDE.  
For token barrier, you need to switch to 'noAuth' to run the test cases.  
Before the test please run 'npm install' in /project/server and /project/client.
The test cases are run by 'npm test' in /project/server and /project/client.

# Resources
SIS Import Format Documentation: https://canvas.instructure.com/doc/api/file.sis_csv.html  
Client meeting Slides: https://drive.google.com/drive/folders/1KsruCEazM1LIEwYIiSFE5l8VLQ7VwDuL  
Project status reports: https://drive.google.com/drive/folders/1yF1JvwldXOBQssMNVlRAmPKCERXNM9kJ  
