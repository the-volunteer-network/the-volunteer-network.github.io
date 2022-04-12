---
title: REST Service Endpoint
description: REST service endpoint documentation.
menu: Endpoint
order: 90
---

## REST service endpoint 

#### /organizations[GET] 
- Retrieves all the organizations from the database
- No authentication required
- Mediatype : application/json

#### /organizations[GET]
- Searches and retrieves the specified organizations.
- No authentication required
- Query String "q" required to initiate the query.
- Mediatype : application/json

#### /organizations[POST]
- Adds an organization to the database.
- No authentication required
- @RequestBody: organization object 
- Mediatype : application/json

#### /organizations/{organizationId}[GET]
- Selects and returns an organization specific to its id.
- @PathVariable : organizationId
- Mediatype : application/json

#### /organizations/{organizationId}[PUT]
- Modifies the specifies organization.
- No authentication required
- @PathVariable : organizationId
- Mediatype : application/json
#### /organizations/{organizationId}[DELETE]
- Deletes the specified organization.
- No authentication required
- @PathVariable : organizationId

#### /organizations/{organizationId}/name[GET]
- Retrieves the name of the specified organization from the database
- No authentication required
- @PathVariable : organizationId
- Mediatype : application/json

#### /organizations/{organizationId}/name[PUT]
- Add the name of the organization to the database
- No authentication required
- @PathVariable : organizationId
- @RequestBody: String name
- Mediatype : application/json

#### /organizations/{organizationId}/opportunities[GET]
- Requests all of the opportunities from the database.
- No authentication required
- @PathVariable : organizationId
- Mediatype : application/json

#### /organizations/{organizationId}/opportunities[GET]
- Searches and retrieves a specified opportunity from the database.
- No authentication required
- @PathVariable : organizationId
- Query String "q" required to initiate the query.
- Mediatype : application/json

#### /organizations/{organizationId}/opportunities[POST]
- Adds an opportunity to the database.
- No authentication required
- @PathVariable : organizationId
- @RequestBody: opportunity object
- Mediatype : application/json

#### /organizations/{organizationId}/opportunities/{opportunityId}[GET]
- Retrieves a specified opportunity specific to an organizationId and an opportunityId.
- No authentication required
- @PathVariable : organizationId
- @PathVariable: opportunityId
- Mediatype : application/json

#### /organizations/{organizationId}/opportunities/{opportunityId}[PUT]
- Modifies the specified opportunity specific to an organizationId and an opportunityId.
- No authentication required
- @PathVariable : organizationId
- @PathVariable: opportunityId
- @RequestBody: opportunity object
- Mediatype : application/json

#### /organizations/{organizationId}/opportunities/{opportunityId}[DELETE]
- Deletes the specified opportunity specific to an organizationId and an opportunityId.
- No authentication required
- @PathVariable : organizationId
- @PathVariable: opportunityId
- Mediatype : application/json

#### /users/me[GET]
- Retrieves the current user.
- No authentication required
- @RequestBody: user object
- Mediatype : application/json

#### /users/me[PUT]
- Modifies the current user.
- Retrieves the current user.
- No authentication required
- Mediatype : application/json

####  /users/me/favorites[GET]
- Retrieves the specified instance of favorite the user is tied to.
- No authentication required
- Mediatype : application/json
#### /users/me/favorites/{organizationId}[GET]
- Retrieves the organization if it has been marked as favorite by the user.
- No authentication required
- @PathVariable : organizationId
- Mediatype : application/json

#### /users/me/favorites/{organizationId}[PUT]
- Sets the specified  organization as favorite if it has been marked as favorite by the user.
- No authentication required
- @PathVariable : organizationId
- @RequestBody: Boolean favorite
- Mediatype : application/json

#### /users/me/organization[GET]
- Retrieves the owned organization for the specific user.
- No authentication required
- Mediatype : application/json

#### /users/me/volunteers[GET]
- Retrieves all the instances of volunteers the user is tied to.
- No authentication required
- Mediatype : application/json

#### /users/me/volunteers/{organizationId}[GET]
- Retrieves all the instances of volunteers the user is tied to.
- No authentication required
- @PathVariable : organizationId
- Mediatype : application/json

#### /users/me/volunteers/{organizationId}[PUT]
- Sets the user as volunteers for a specific organization.
- No authentication required
- @PathVariable : organizationId
- @RequestBody: Boolean volunteer
- Mediatype : application/json

