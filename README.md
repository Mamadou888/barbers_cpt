# Barbers Backend - Cut Bus
> Mamadou-Sadio Diallo (mamadou)

## Overview
This python project is a backend categorizing barbers for people with coarse or curly hair.

## Background
I'm excited to bring together barbers that serve people with coarse or curly hair because it's usually hard to find and make appointments with these barbershops, especially if it's your first time. These specfic barbershops are often left behind in this "tech revolution" because they operate in such an old-school, fundementals-only, manner. You come in with cash, wait your turn, get cut, and leave.

For context, my friends and I have needed this when we were trying to get haircuts when we find ourselves in a new place. It solves the specfic problem of making a trip to a barbershop and finding out that they don't have time to cut your hair, so you have to leave and come back another time. Worse yet, is when you go to the barbershop and they only take cash (which is most of them). Then you either have to pay some atm fee or leave and go find a bank. 

I've had expereince working on the frontend of websites but not much with the backend and managing databases and GETing and POSTing data. 

## Implementation
At a high level, in order to implement my project, I plan on gathering as much data about barbers as possible that I can find on the internet. Than I'll use a backend database such as FireBase (or any other one you suggest) and store the barbers there. I'll also allow a way for barbers to sign themseles up and addthemselves to the database. I will use a python webserver such as Flask to manipulate and manage all that data. 

The project breaks down into a few jobs (open to feedback on this): Setting up Flask. Designing how the url's will work. Calling API's like Yelp and GMaps. Storing that data in Firebase. Setting up a way for Barbers to sign themselves up. Allow clients to access this data. Allow clients to see the times barbers are free. All these peices will be connected via Flask. i don't particularly know exactly what Python Packages to make use of but I for sure know I'll be making heavy use of the Requests module.

## Tasks
1. Set up Flask (2 hours)
2. Connect Online Database (1 hour)
3. Allow Barbers to Make Accounts (2 hours)
4. Allow Client to request Accounts (1 hour)
5. *(Stretch)* Create an interactive front end for all this to be managed on
6. *(Stretch)* Add bootstrap and cool CSS features to that Frontend
7. *(Stretch)* Grab Barbers from API's like GMaps and Yelp and also intergrate them into the database

I think it's feasible to set up flask and set up a few requests going to and from the database. I think it will be tediuous trivial to set up a front end where users can login and make accounts and such. 

## Resources
I'll be using plenty of requests to a potential database, perhaps Firebase? (only one I really know). I'll have to host this web app on a server, I was thinking Amazon Web Services, mainly because I have a coupon for it. 
