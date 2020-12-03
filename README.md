# youTrack

## Problem Statement
This is a solution to the problem statement given for the vGHC hackathon. We chose the theme of Navigation. 
Our main aim is to create an interactive platform for the delegates via mobile and web app. 

This project is aimed to provide users a hassle-free experience at the conference, by helping them navigate through the events with the help of a map. This project is a combination of a mobile and a web app that will interact with each other through web sockets. While the app is meant for the attendees the web app can be used by the organizers of the event. Both the mobile app and the web app have the same backend, which will be connected to the database that stores the details of the attendees such as registration ID, name, mail ID, and phone number, and their location.


## Mobile App:
The user has to login first, though wifi.
* Once connected to the wifi, their location, with their details will be updated in the database.
* Once logged in the user can view the map and their real-time location. 
* The wifi RTLS( Real-Time Location System) will continuously update their location as they move and it will be sent to the backend. 
* The user can choose where they want to go and check the availability of seats at a particular hall. 
* The app will help them to navigate to the particular hall of their choice.
* Upon clicking on a particular location, the app will show a pop up which consists of brief info about that particular stall/hall.


  

## Web App:
* The Web app will show the map of the entire venue 
* It will show the pointer positions of the logged-in users on the map
* It will show the traffic at the venue using heat maps.
* Upon clicking, on a particular pointer of the user, it will show a pop-up, with the details of the user. 
* The app can search for users through the search box. 



## Technologies Used:
* Visual Studio Code
* Android Studio Code 
* AutoCAD
* React Native
* NodeJS
* Mapbox
* HTML/ CSS/ JavaScript
* Web sockets.
