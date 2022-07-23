Daily learning

# Cloud Parking

# Performing a Cloud Deployment of a set of APIs developed in Spring Boot

Project developed at Digital Innovation One's Bootcamp Spring Framework Experience with expert guidance [Sandro Giacomozzi](https://github.com/sandrogiacom "Sandro Giacomozzi"). 
Learning to develop a set of APIs using Spring Boot to control a parking lot. Controls entry, exit and amount to be charged from the customer. Application of all API development best practices, including security with Spring Security and access to the PostgreSQL database. Conducting tests and test coverage reports. Execution of the Heroku cloud deployment to make the API available on the Internet.

## Run database
docker run --name parking-db -p 5432:5432 -e POSTGRES_DB=parking -e POSTGRES_USER=admin -e POSTGRES_PASSWORD=123 -d postgres:10-alpine

## Start and Stop

### Stop Database
docker stop parking-db

### Start Database
docker start parking-db

[LICENSE](./LICENSE)
