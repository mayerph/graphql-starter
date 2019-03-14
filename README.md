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

- Serve the apollo playground
```
http://localhost:8000/graphql
```

# Credentials
| User | Password | Description
| ---------------------------------------------- | -----------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| admin                                   | sterne123     | the user is assigned to all permissions
| reader                                   | sterne123     | the user has only read permissions

