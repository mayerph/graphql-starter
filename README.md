# graphql-starter
This projects starts three docker container. One for the front-end, one for the back-end and one for the database. In combination they represent a working web-based client/server application. 

# Pre-requirements

To build and run this app locally you will need a few things:

-   Install Docker ([Mac](https://runnable.com/docker/install-docker-on-macos), [Windows](https://runnable.com/docker/install-docker-on-windows-10))
-   Install [VS Code](https://code.visualstudio.com/)


# Getting started

- Clone the repository
```
git clone https://github.com/mayerph/graphql-starter.git
```

- Start the docker-containers
```
docker-compose up
```

- Serve the application
```
http://localhost:8080/
```

- Serve the apollo playground</br>(For a detailed description working with apollo in the context of this project click [here](https://github.com/mayerph/grapqhl-server-starter#operations))
```
http://localhost:8000/graphql
```


# Credentials
| User | Password | Description
| ---------------------------------------------- | -----------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| admin                                   | sterne123     | the user is assigned to all permissions
| reader                                   | sterne123     | the user has only read permissions

For a detailed description click [here](https://github.com/mayerph/grapqhl-server-starter#default-application-data)

# Components
## Front-End
[View it on GitHub](https://github.com/mayerph/graphql-client-starter)

## Back-End
[View it on GitHub](https://github.com/mayerph/grapqhl-server-starter)

## MongoDB
[Offical website](https://www.mongodb.com/what-is-mongodb)

# Further possibilities
## docker-compose up
- Starting the complete environment
```
docker-compose up
```

- Starting the back-end</br>In this case the back-end includes the back-end itself and the mongodb
```
docker-compose -f docker-compose-backend.yml up
```

## changing the environment
By default the application starts in the testing mode. To start the application in production mode you have to modify the docker-compose.yml file and change the env_file properties to "production.env"
