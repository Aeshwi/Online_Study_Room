# Online_Study_Room

## Features Of The Project:
● In the project we have created a study room in which many users can interact with each
other by making rooms on different topics.
● There are many templates like home, room, user, activity component, feed component,
topics component, delete, room form and login register.
● Users can create a room, edit a room or can delete a room.
● Users can chat with other user by sending messages in the room and can also edit and
delete their messages.
● In the home page we have shown the list of topics, rooms and the recent activity which
includes list of all recent chat.
● In the room we have list of chats for the particular room and the list of participants of that
room.
● The user can login or register by login register form template.
● The user page of a particular pages contains lit of all topics, the room created by user
and the chats by the particular user in all rooms.

## Installation:
In our project we have used django for developing our online study room so following are the
steps for installing it.
Steps to Install Django
1) Install virtual environment - Enter following command in cmd
pip install virtualenv
2) Set Virtual environment- Setting up the virtual environment which will allow us to edit the
dependency which generally your system wouldn’t allow.
   Follow these steps to set up a virtual environment
   1. Create a virtual environment by giving this command in cmd:
   virtualenv env_site
   2. Change directory to env_site by this command:
   cd env_site
   3. Go to Scripts directory inside env_site and activate virtual environment:
   cd Scripts
   activate
3) Install Django- Install django by giving following commandpip install django
4) Return to the env_site directory by using the following command:
cd ..
5) Start a project by following command:
django-admin startproject studyroom
6) Change directory to studyroom
cd studyroom
7) Start the server by typing following command in cmd:
python manage.py runserver
8) To check whether server is running or not go to web browser and enter http://127.0.0.1:8000/
as url.

Steps to be executed on cmd to execute the project In cmd:
1. cd Documents
2. cd studyroom
3. pip install django
4. django-admin
5. env\scripts\activate
6. python manage.py runserver
Steps to be executed on cmd to execute the project In VS:
c:/Users/vanib/Documents/studyroom/env/Scripts/Activate.ps1

## Working of the Project Internally:<br />
● A url file is created in which all the urls are kept and when a particular url appears then it
searches for it in the url file then it is directed to views file and to a particular function
which is mentioned in the url<br />
● And then it executes the function.<br />
● The objects which need to be rendered out in the template are passed in context
dictionary and at the end of the function are passed in the return method which directs
its to the template in which the objects should be rendered.<br />
