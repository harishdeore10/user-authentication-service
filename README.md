# RESTFull API

DEVELOP A WEB API WHICH IS/CAN BE EASILY HOSTED ON A DOCKER IMAGE THAT DOES THE FOLLOWING STEPS:
DEVELOP A WEB API TO ADD USERS TO A COMMONLY AVAILABLE DB
CONSTRUCT WEB API'S TO HANDLE A CRUD OPERATION FOR AN ENTITY
DEVELOP AN API TO READ AN XLS FILE AND PARSE THE DATA AND SAVE TO DB (VALIDATE THE FILE DATA, FILE FORMAT AND SIZE)
EXPOSE AN API THAT CAN RETRIEVE A TOKEN FOR AUTHENTICATION (THAT WILL BE USED WHEN YOU ARE INVITED FOR NEXT STAGES OF SELECTION)
DEVELOP AN API TO HANDLE MULTI-TENANT ACTIVITY (MAINTAIN TWO ENTITIES IN THE SYSTEM , ONE ENTITY BELONGING TO ONE PARTICULAR CLIENT SHOULDN'T BE VISIBLE TO ANOTHER CLIENT)


### Purpose
This project uses [Maven](https://maven.apache.org/) 

### Version
This project uses:
- Eclipse Oxygen
- Maven 2
- Java 1.8
- Hibernate 5.3.6
- H2 In Memory Database 1.4

 
### Rest End Points
> To register user

http://localhost:8080/register

{
"username": "admin",
"password": "password"
}

> To get JWT Token

http://localhost:8080/authenticate

{
"username": "admin",
"password": "password"
}

> To get all users detail

http://localhost:8080/users

In header please add JWT Token.

  