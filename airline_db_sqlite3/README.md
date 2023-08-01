# Dockerfile
The dockerfile is taken as the standard docker file created using: 
$ docker init

# Compose.yaml
Defines 2 services:
 - db (database)
 - web (django server)

https://dev.to/foadlind/dockerizing-a-django-mysql-project-g4m


# Running application
$ docker compose up -d
(d flag runs in detached mode)

To run manage.py commands in the Django container (web):
$ docker-compose run --rm web python manage.py migrate

The read write for the SQLite 3 app is added via
https://www.youtube.com/watch?v=UGnNGvEXlFY