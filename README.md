# This project uses Spring boot as a server and an Android client application.

# Spring Boot Rest API:-
 
 We have created two endpoints like this:-

| Http Method | URL     | Description  | 
| :-------- | :------- | :------------------------- |
| **GET** | /cems/event | Retrieve all events |
| **POST** | /cems/event | Create a new event |

# Android Application:-

In this Application, We will create a new Android application that will work as a client to the Spring Boot Server. For connecting to the REST API, we will use Retrofit dependency.

# Event Form Activity
In this activity, We will create a form GUI for entering event details. Once the form is filled and the save button is pressed, the object will be sent to the server via POST request. The server will then accept the POST request and saves the event into the MySQL database.

# Events List Activity
We will fetch all the event data from the Spring Boot Server and show it in an Android RecyclerView. 
And as soon as the app starts, we will put a splash screen for a few seconds.

