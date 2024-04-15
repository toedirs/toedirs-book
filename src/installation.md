# Installation

## Docker Compose

This is the recommended way to set up Toedi.

Simply grab the docker-compose.yml file from the [main github 
repo](https://github.com/Panaetius/toedirs/blob/main/docker-compose.yml).

Change the `POSTGRES_PASSWORD` environment variable for the postgres image and 
also update it in the `DATABASE_URL` for the toedirs image 
(`postgres://toedi:<password>@db:5432/toedi`).

Run 
```
$ docker compose up   
```
to start the application.
