# TDEI-usermanagement-manual
User management manual for TDEI system
# User management Front-end portal manual
[User management front end](https://tdei-user-management-front-end-dev.azurewebsites.net/) enables, user and TDEI entity management operations. Operations are feature enabled for different user personas. Details of different user personas and thier roles and responsibilites are further described in this document.

There are two main personas used in the application based on the user type. 
1. Admin persona
2. Non-admin persona 


# Admin persona
- Admin can perform below actions 
    - [Create an organization](./create-org.md)
    - [Assign POC to an organization](./assign-poc.md)
    - [Create Service](./create-service.md)
    - [Create Station](./create-station.md)
- Currently admin roles are added from system backend.

# Non-Admin persona
- There are multiple roles a non-admin persona can have. The roles include
    - `POC` for an organization
    - `flex-data-generator` for an organization
    - `pathways-data-generator` for an organization
    - `osw-data-generator` for an organization

## POC
- Organization point of contact can perform below actions
    - [Create service](./create-service.md)
    - [Create station](./create-station.md)
    - [Assign permissions to the users](./assign-role.md)

## Other users
- [User registration](./user-registration.md)
