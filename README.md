﻿# taxi-service
Hello!
This is my small application - taxi_service

A little about it’s functionality:
To use the app, you need to register a profile as a Driver of our Taxi_Service. After registration - you need to log in, to access app’s entire functionality. Here you also can registrate cars and their manufacturers, look through a list of all registrated cars, drivers or manufacturers and delete any of them if needed. Moreover you are able to connect certain driver(s) to a certain car. Logout is implemented too. After pushing "logout" button - only login with registration page will be accessable again. 

While creating the app I used 3-tier structure:
1. DAO - this tier is responsible only for insertion and extraction data from database.
2. Service - this tier is responsible for opereting this data, realization of our program’s logic.
3. Controller - this tier is responsible for communicating with user. It can handle the users’ inputs and show the needed information from them.

Also, the app is based on SOLID principles: 
1. Each class have only one responsibility.
2. It is open for extension, but closed for modification.
3. Objects of a superclass are replaceable with objects of its subclasses.
4. Large interfaces are split into smaller ones, where it was reasonable.
5. High-level and low-level modules depends on abstractions.

If you want to use this app locally(IntelliJ IDEA Ultimate is needed) on your device you need to set up tomcat: 
Run your project in Intelegi IDEA -> edit configuration -> add new configuration -> tomcat -> local -> fix -> `your project name`_war_exploded. 
And I recomend you to put aplication context: "/" just for your comfort.
I hope my app will be useful for you!
