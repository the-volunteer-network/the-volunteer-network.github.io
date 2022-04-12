---
title: Outlines of technology stacks
description: User and build instructions, technical requirements and dependencies.
menu: Technology inventory
order: 80
---

## Back-end
- Apache maven 
- Maven Javadoc
- Spring Hateoas
- Preload json file
- Web service application, incorporating:
   - Data model
   - Hibernate ORM
   - JPA
Custom entity classes
- Spring Boot Data
- Custom data repository interfaces
- Service controllers
  - Spring MVC
  - Custom controller classes
- View composition & serialization
  - Jackson JSON
  - Custom view classes & interfaces
- Authentication
  - Spring Framework Security
  - Google Sign In (external service; see https://developers.google.com/identity)


## Front-end

- Android SDK 31
- Data model
  - H2 database
- Custom type converters
- DTO Classes
- Google material design
- Google Map
- Retrofit
- ReactiveX
- Gson
- OkHTTP libraries
- Custom serializer/deserializers
- Viewmodel components
   - Android Lifecycle framework (ViewModel & LiveData)
   - Custom viewmodel classes
- View
   - Custom RecyclerView.Adapter and RecyclerView.Holder classes
   - Custom layouts
- Controller
  - Custom activity and fragment classes
- Authentication
  - Google Sign In (external service; see https://developers.google.com/identity)
  - Custom sign in service class