# This Repository contains MongoDB, MySQL, PostgreSQL docker-compose files to run the database(Only server) without having to do any setup process

## Prerequisites:

#### Docker

#### Docker Compose

#### GUI management tools like Compass for mongoDB, Workbench for MySql, and PGAdmin for PostgreSQL (Optional)

## Instructions

#### Each of the 3 folders contains the docker compose files, and the environment variables files for each of the databases.

<br>

#### There is a sample-env.env file in each folder, which contains the environment variables for the docker-compose file.

<br>

#### Using these files, you can create the final .env files to run the compose. The final file should be saved as [mysql|postgres|mongo]-env.env

#### The compose files are configured to use a <b>PRECONFIGURED VOLUME</b>, so either comment out the "external:true" in the volumes section of the compose file or create a blank volume manually using "docker volume create <name>".

<br>

### To run the docker-compose file, open a terminal/cmd session in the respective folder and run:

#### 1) docker-compose up -d (For detached mode)

#### 2) docker-compose up (For interactive mode)
