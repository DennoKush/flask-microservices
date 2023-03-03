## Building Flask Microservices

Microservices are an approach to distributed systems that promote the use of finely grained services with their 
own lifecycles, which collaborate together. Because microservices are primarily modeled around
business domains, they avoid the problems of traditional monolithic architectures.

This project has 4 different microservices, `user`, `book`, `order` and `frontend`. They are 
lightweight, independently deployable, testable and managed.

### Table of contents
- [How to run the project](How to run the project)
- [Resources](Resources)

#### How to run the project

cd into the frontend directory and fun this command
```commandline
docker-compose -f docker-compose.deploymennt.yml up -d
```

#### Resources
- [Flask]('https://flask.palletsprojects.com/en/2.2.x/quickstart/')
- [Docker]('https://www.docker.com/get-started/')
- [Docker Compose]('https://docs.docker.com/compose/gettingstarted/')








































