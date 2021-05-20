# RabbitMQ-Demo
Explore AMQP through Docker and RabbitMQ

## Pre-reqs

Have docker-compose and docker engine (v18.06.0+) installed and configured. 

- For Windows & Mac OS: Docker Desktop installation packs both Docker Engine and Docker Compose. 
- For Linux based OS: users may have to install Docker (Engine) and Docker Compose separately.

Docker and Docker compose installation can be checked through `docker -v` and `docker-compose -v` on most OS.

## Run RabbitMQ

Clone this repository or download the `docker-compose.yml` file.

Run following command in the root of repository or directory where the docker-compose.yml is placed:

- For Windows: `docker-compose up`
- For Linux/Unix(Mac) based OS: `sudo docker-compose up`

If everthing goes well, RabbitMQ server GUI will be live at http://localhost:15672/

Log in with **rabbitmq** is the username and password. 

Use `Ctrl+C` to stop docker-compose and hence RabbitMQ

## Simple GUI based Tutorial

A very basic intro video to **RaabitMQ** is available at: https://www.youtube.com/watch?v=deG25y_r6OY 

Follow a simple tutorial in the latter part of the above video about RabbitMQ: https://youtu.be/deG25y_r6OY?t=235