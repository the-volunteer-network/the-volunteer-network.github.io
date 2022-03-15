---
title: Implementation
description: Entity, repository, view and controller classes.
menu: Implementation
order: 20
---

## Service

### Entity Classes

* [`User`](https://github.com/the-volunteer-network/tvn-service/blob/main/src/main/java/edu/cnm/deepdive/tvnservice/model/entity/User.java)
* [`Organization`](https://github.com/the-volunteer-network/tvn-service/blob/main/src/main/java/edu/cnm/deepdive/tvnservice/model/entity/Organization.java)
* [`Opportunity`](https://github.com/the-volunteer-network/tvn-service/blob/main/src/main/java/edu/cnm/deepdive/tvnservice/model/entity/Opportunity.java)

## Database Class

- [`Database`]()

- ## DAO Interfaces 

- [`User`](https://github.com/the-volunteer-network/tvn-service/blob/main/src/main/java/edu/cnm/deepdive/tvnservice/model/dao/UserRepository.java)
- [`Organization`](https://github.com/the-volunteer-network/tvn-service/blob/main/src/main/java/edu/cnm/deepdive/tvnservice/model/dao/OrganizationRepository.java)
- [`Opportunity`](https://github.com/the-volunteer-network/tvn-service/blob/main/src/main/java/edu/cnm/deepdive/tvnservice/model/dao/OpportunityRepository.java)


## ViewModel Class
- [`LoginViewModel`](https://github.com/the-volunteer-network/tvn-client/tree/main/app/src/main/java/edu/cnm/deepdive/tvnclient/viewmodel)


## Rest Controller && Application logic services

- [`UserService`](https://github.com/the-volunteer-network/tvn-service/blob/main/src/main/java/edu/cnm/deepdive/tvnservice/service/UserService.java)
- [`UserConverter`](https://github.com/the-volunteer-network/tvn-service/blob/main/src/main/java/edu/cnm/deepdive/tvnservice/service/UserConverter.java)
- [`OrganizationService`](https://github.com/the-volunteer-network/tvn-service/blob/main/src/main/java/edu/cnm/deepdive/tvnservice/service/OrganizationService.java)
- [`OpportunityService`](https://github.com/the-volunteer-network/tvn-service/blob/main/src/main/java/edu/cnm/deepdive/tvnservice/service/OpportunityService.java)
- [`AbstractUserService`](https://github.com/the-volunteer-network/tvn-service/blob/main/src/main/java/edu/cnm/deepdive/tvnservice/service/AbstractUserService.java)
- [`AbstractOrganizationService`](https://github.com/the-volunteer-network/tvn-service/blob/main/src/main/java/edu/cnm/deepdive/tvnservice/service/AbstractOrganizationService.java)
- [`AbstractOpportunityService`](https://github.com/the-volunteer-network/tvn-service/blob/main/src/main/java/edu/cnm/deepdive/tvnservice/service/AbstractOpportunityService.java)

## Oauth 2.0 resource server
- [` `]()
- [` `]()
- [` `]()



