# dockerAssessment-
This repository contains the solution for Docker and container assessment. 

Docker Practical Assignment
Build a database container image "sample-db". Use these instructions.

Build an application container image "app". Use these instructions.

Create a docker-compose file and ensure that:

A Special network with IP Range 152.15.0.0 Must be used by all services

Use following Environment variables in 'db' service:

MYSQL_USER: <YOURNAME>
MYSQL_PASSWORD: <YOUR-PASSWORD>
MYSQL_DATABASE: orderdb
MYSQL_ROOT_PASSWORD: <ROOT-PASSWORD>
The values written with "<" and ">" are placeholders, you MUST replace with your own values. And remove brackets "<" and ">".

Use following environment variables in "app" service:

DBURL: <MYSQL_USER>
DBNAME: orderdb
DBUSER: <MYSQL_USER>
DBPASS: <MYSQL_PASSWORD>
The values written with "<" and ">" are placeholders, you MUST replace with respective ENVs from "db" service. And remove brackets "<" and ">" .

Build and run application with docker-compose

Share your docker-compose.yaml and both Dockerfile for db and app for assessment .

Share your image-names from docker-hub for assessment.
