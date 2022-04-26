
# Docker compose MS Sql Server with provision

This script will 

- Start Sql server in a docker contaner
- Create a new database
- Crate a new table in the database.
- Insert row in to the database.

Note: Give this a few minutes to start up it needs to add the database. nomrally less than five minutes.

## Connect

    host:  127.0.0.1
    Username : SA
    Password:  password123!

## Start and stop the container.

if you start it as demaon mode and then just dont stop it it should restart when ever you reboot your pc.

#### start 

    docker-compose up

or run as a demon

    docker-compose up -d

### stop

    docker-compose down

# Changes to sql script

If you make any changes to the sql script (create-database) after running it once make sure to do to cause it to rebuild the container with the new sql script.

    docker-compose up --build 


