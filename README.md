# Docker PostgreSQL Shared

Docker compose setup for PostgreSQL with intention of sharing it with multiple projects.

Note: This is meant to be used for development/testing machines only.

## Usage

Copy the `.env.example` file to start using the template. Change the port mapping and root password when necessary.

~~~
cd /path/do/docker-postgres-shared
sudo docker-compose up -d
~~~

## CLI Access

Note: Using the default configuration.

~~~
psql --port 5433 --host 127.0.0.1 --user postgres
~~~
