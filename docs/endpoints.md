---
title: REST Service Endpoint
description: REST service endpoint documentation.
menu: Endpoint
order: 90
---

## REST service endpoint 

#### /organizations[GET] 
##### HTTP Server Spring MVC Controllers
- Retrieves all the organizations from the database
- No authentication required
- Mediatype : application/json

#### /organizations[GET]
##### HTTP Server Spring MVC Controllers
- Searches and retrieves the specified organizations.
- No authentication required
- Query String "q" required to initiate the query.
- Mediatype : application/json

#### /organizations[POST]
##### HTTP Server Spring MVC Controllers
- Adds an organization to the database.
- No authentication required
- @RequestBody: organization object 
- Mediatype : application/json

#### /organizations/{organizationId}[GET]
##### HTTP Server Spring MVC Controllers
- Selects and returns an organization specific to its id.
- @PathVariable : organizationId
- Mediatype : application/json

#### /organizations/{organizationId}[PUT]
##### HTTP Server Spring MVC Controllers
- Modifies the spcifies organization.
- No authentication required
- @PathVariable : organizationId
- Mediatype : application/json
#### /organizations/{organizationId}[DELETE]
##### HTTP Server Spring MVC Controllers
- Deletes the specified organization.
- No authentication required
- @PathVariable : organizationId

#### /organizations/{organizationId}/name[GET]
##### HTTP Server Spring MVC Controllers
- Retrieves the name of the specified organization from the database
- No authentication required
- @PathVariable : organizationId
- Mediatype : application/json

#### /organizations/{organizationId}/name[PUT]
##### HTTP Server Spring MVC Controllers
- Add the name of the organization to the database
- No authentication required
- @PathVariable : organizationId
- @RequestBody: String name
- Mediatype : application/json

#### /organizations/{organizationId}/opportunities[GET]
##### HTTP Server Spring MVC Controllers
- Requests all of the opportunities from the database.
- No authentication required
- @PathVariable : organizationId
- Mediatype : application/json

#### /organizations/{organizationId}/opportunities[GET]
##### HTTP Server Spring MVC Controllers
- Searches and retrieves a specified opportunity from the database.
- No authentication required
- @PathVariable : organizationId
- Query String "q" required to initiate the query.
- Mediatype : application/json

#### /organizations/{organizationId}/opportunities[POST]
##### HTTP Server Spring MVC Controllers
- Adds an opportunity to the database.
- No authentication required
- @PathVariable : organizationId
- @RequestBody: opportunity object
- Mediatype : application/json

#### /organizations/{organizationId}/opportunities/{opportunityId}[GET]
##### HTTP Server Spring MVC Controllers
- Retrieves a specified opportunity specific to an organizationId and an opportunityId.
- No authentication required
- @PathVariable : organizationId
- @PathVariable: opportunityId
- Mediatype : application/json

#### /organizations/{organizationId}/opportunities/{opportunityId}[PUT]
##### HTTP Server Spring MVC Controllers
- Modifies the specified opportunity specific to an organizationId and an opportunityId.
- No authentication required
- @PathVariable : organizationId
- @PathVariable: opportunityId
- @RequestBody: opportunity object
- Mediatype : application/json

#### /organizations/{organizationId}/opportunities/{opportunityId}[DELETE]
##### HTTP Server Spring MVC Controllers
- Deletes the specified opportunity specific to an organizationId and an opportunityId.
- No authentication required
- @PathVariable : organizationId
- @PathVariable: opportunityId
- Mediatype : application/json

####/users/me[GET]
##### HTTP Server Spring MVC Controllers
- Retrieves the current user.
- No authentication required
- @RequestBody: user object
- Mediatype : application/json

####/users/me[PUT]
##### HTTP Server Spring MVC Controllers
- Modifies the current user.
- Retrieves the current user.
- No authentication required
- Mediatype : application/json

####  /users/me/favorites[GET]
##### HTTP Server Spring MVC Controllers
- Retrieves the specified instance of favorite the user is tied to.
- No authentication required
- Mediatype : application/json
#### /users/me/favorites/{organizationId}[GET]
##### HTTP Server Spring MVC Controllers
- Retrieves the organization if it has been marked as favorite by the user.
- No authentication required
- @PathVariable : organizationId
- Mediatype : application/json

#### /users/me/favorites/{organizationId}[PUT]
##### HTTP Server Spring MVC Controllers
- Sets the specified  organization as favorite if it has been marked as favorite by the user.
- No authentication required
- @PathVariable : organizationId
- @RequestBody: Boolean favorite
- Mediatype : application/json

#### /users/me/organization[GET]
##### HTTP Server Spring MVC Controllers
- Retrieves the owned organization for the specific user.
- No authentication required
- Mediatype : application/json

#### /users/me/volunteers[GET]
##### HTTP Server Spring MVC Controllers
- Retrieves all the instances of volunteers the user is tied to.
- No authentication required
- Mediatype : application/json

#### /users/me/volunteers/{organizationId}[GET]
##### HTTP Server Spring MVC Controllers
- Retrieves all the instances of volunteers the user is tied to.
- No authentication required
- @PathVariable : organizationId
- Mediatype : application/json

#### /users/me/volunteers/{organizationId}[PUT]
##### HTTP Server Spring MVC Controllers
- Sets the user as volunteers for a specific organization.
- No authentication required
- @PathVariable : organizationId
- @RequestBody: Boolean volunteer
- Mediatype : application/json

