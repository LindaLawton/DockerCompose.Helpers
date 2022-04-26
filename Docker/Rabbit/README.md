# DockerCompose file for RabbitMQ

This script will 

- Add a docker container RabbitMq + Erlang
- Adds managment ui endpoint http://localhost:8080/#/

## Connect

    - http://localhost:8080/#/
    - Login: guest
    - Password: guest

## Start and stop the container.

if you start it as demaon mode and then just dont stop it it should restart when ever you reboot your pc.

#### start 

    docker-compose up

or run as a demon

    docker-compose up -d

### stop

    docker-compose down