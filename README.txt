# Docker-Redmine+MYSQL

First it need to Install docker compose
=========================================
Use this link.
https://github.com/docker/compose/releases

Steps
======
 1  Clone the YML file form Git Hub
        $  git clone https://github.com/sumithdasa/Docker-redmine
 the clone operation create a new directory called Docker-redmine.
 2 Change the directory into Docker-redmine
        $  cd Docker-redmine
 3   Bring up compose app
        $ docker-compose up -d
  4 check the current state (UP or not)
        $ docker-compose ps command.
  5 visit 
         http://localhost:8080, or http://host-ip:8080 (as appropriate).
  6 Default username and passworkd for redmine is
    UN-Admin P-Admin
    (You can change it after the first login)

