---
title: Overview
description: Project summary and roster.
menu: Overview
order: 0
---

## Summary

[//]: # (The volunteer network is an app designed for everyone who is looking to volunteer but doesn't know where to start.)

[//]: # (The app lists all the of the places in your area looking for people to volunteer and where they can offer their service.)
  The Volunteer Network is an application that aims to connect volunteers with various organizations that need assistance in accomplishing their goals. Using their location and information about their skills, users will be able to provide organizations that are in need of particular or general skills in their area.  


## Intended users

- Successful local business owners looking for ways to network and give back to their community by volunteering.

>As a successful business owner looking to give back to my community, I have always wanted to volunteer, but I have no idea of where I could offer my time.
> I would love to have a resource that would help me connect with volunteering opportunities.

- People who recently moved into a new town looking to meet new friends and introduce themselves to their community by volunteering.

> As someone who recently moved from out of state, I am always looking for ways to make new acquaintances and provide to this city that has been so welcoming.
> Volunteering is a great place to start, having an app that points me  directly to places where people actually need my help would be great!
 




## Client component

### Functionality

- Welcoming screen where the user could pick their search location area. 
- A map of the search area the user typed in, will then get deployed with all the places looking for volunteers.
- The user could then filter some criteria in a search bar where a list of available volunteering opportunities would show up.
- A Calendar could also be available on a different screen with volunteering opportunities.
- The user would have the availability to refer to the history of their past check ins  and past volunteering events.
- On a separate screen a list of contact info and direct email of places looking for volunteer would also be available.
- The user would also have the opportunity to access and favorite their preferred places to volunteer at.
- A Notification of new availability would also be available, if the user wishes to subscribe to it, letting them know of any new volunteering opportunity.


### Persistent data

- History of check ins
- Favorite volunteering place
- Stored and saved data of past activities
- Name and location of the user
 
    
### Device/External services

- [Google Sign In](https://developers.google.com/identity/sign-in/android/start-integrating)
  - Distinguish between users and offer privacy on shared devices.
  - The app is not accessible without internet connection.
- [Google Maps Geolocation](https://developers.google.com/maps/documentation/geolocation/overview)  
  - The application will use Geolocation to populate a map with the volunteering opportunities available.
  - The application will still function, but will not be able to display the map, and instead provide only textual returns.
- [Android Direct Messaging](https://developer.android.com/reference/android/os/Messenger)  
  - The application will use the Messenger function to relay conversations between organizations and individual users.
  - The application will still function, but will not be able to provide real-time messaging between user and organization, but the two will still be able to communicate provided the user listed email or phone number.

 
## Server component

TBD

### Functionality

- Provide lists of volunteering opportunities.
- Locate volunteer locations that have been added to the database and then process that information in a way that is useful for the android app to display in an appropriate map.
- Preparing and processing data and text stored in the database and accessed from the database.

### Persistent data

- History of check ins
- Favorite volunteering place
- Stored and saved data of past activities
- Name/location of the user 
 
## Stretch goals/possible enhancements 

- Forum
- Live and direct update from the volunteer places


