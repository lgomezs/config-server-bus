Spring Cloud Config Refresh Strategies
==========================


# Generate Library

    mvn clean install 

# start docker

    docker-compose up

# add to your host.conf

    127.0.0.1 kafka-server

# start application

    mvn spring-boot:run

Test the config server by typing the following config server URL in your browser:

    http://localhost:8888/app-identity/app/master


## View application config client




