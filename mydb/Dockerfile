FROM postgres:latest

ENV POSTGRES_USER "steve"
ENV POSTGRES_PASSWORD "test1234"
ENV POSTGRES_DB "dockerdb"

WORKDIR "/appdb"

COPY "init.sql" "/docker/db-entrypoint-initdb.d" 

EXPOSE 5432

VOLUME [ "/var/postgres/pgdata:mydb_v" ]