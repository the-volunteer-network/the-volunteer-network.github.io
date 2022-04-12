---
title: REST Service Endpoint
description: REST service endpoint documentation.
menu: Endpoint
order: 90
---


## REST service endpoint 

#### /organizations[GET] 
##### HTTP Server Spring MVC Controllers
- Retrieves all of the organizations from the database

#### /organizations[GET]
##### HTTP Server Spring MVC Controllers
- Searches and retrieves the specified organizations.

#### /organizations[POST]
##### HTTP Server Spring MVC Controllers
- Adds an organization to the database.

#### /organizations/{organizationId}[GET]
##### HTTP Server Spring MVC Controllers
- Selects and returns an organization specific to its id.

#### /organizations/{organizationId}[PUT]
##### HTTP Server Spring MVC Controllers
- Modifies the spcifies organization.

#### /organizations/{organizationId}[DELETE]
##### HTTP Server Spring MVC Controllers
- Deletes the specified organization.

#### /organizations/{organizationId}/name[GET]
##### HTTP Server Spring MVC Controllers
- Retrieves the name of the specified organization from the database

#### /organizations/{organizationId}/name[PUT]
##### HTTP Server Spring MVC Controllers
- Add the name of the organization to the database

#### /organizations/{organizationId}/opportunities[GET]
##### HTTP Server Spring MVC Controllers
- Requests all of the opportunities from the database.

#### /organizations/{organizationId}/opportunities[GET]
##### HTTP Server Spring MVC Controllers
- Searches and retrieves a specified opportunity from the database.

#### /organizations/{organizationId}/opportunities[POST]
##### HTTP Server Spring MVC Controllers
- Adds an opportunity to the database.

#### /organizations/{organizationId}/opportunities/{opportunityId}[GET]
##### HTTP Server Spring MVC Controllers
- Retrieves a specified opportunity specific to an organizationId and an opportunityId.

#### /organizations/{organizationId}/opportunities/{opportunityId}[PUT]
##### HTTP Server Spring MVC Controllers
- Modifies the specified opportunity specific to an organizationId and an opportunityId.

#### /organizations/{organizationId}/opportunities/{opportunityId}[DELETE]
##### HTTP Server Spring MVC Controllers
- Deletes the specified opportunity specific to an organizationId and an opportunityId.


####/users/me[GET]
##### HTTP Server Spring MVC Controllers
- Retrieves the current user.

####/users/me[PUT]
##### HTTP Server Spring MVC Controllers
- Modifies the current user.

####  /users/me/favorites[GET]
##### HTTP Server Spring MVC Controllers
- Retrieves the specified instance of favorite the user is tied to.

#### /users/me/favorites/{organizationId}[GET]
##### HTTP Server Spring MVC Controllers
- Retrieves the organization if it has been marked as favorite by the user.

#### /users/me/favorites/{organizationId}[PUT]
##### HTTP Server Spring MVC Controllers
- Sets the specified  organization as favorite if it has been marked as favorite by the user.

#### /users/me/organization[GET]
##### HTTP Server Spring MVC Controllers
-Retrieves the owned organization for the specific user.

#### /users/me/volunteers[GET]
##### HTTP Server Spring MVC Controllers
- Retrieves all the instances of volunteers the user is tied to.

#### /users/me/volunteers/{organizationId}[GET]
##### HTTP Server Spring MVC Controllers
- Retrieves all the instances of volunteers the user is tied to.

#### /users/me/volunteers/{organizationId}[PUT]
##### HTTP Server Spring MVC Controllers
- Sets the user as volunteers for a specific organization.
