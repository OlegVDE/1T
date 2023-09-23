FROM postgres:latest
ENV POSTGRES_DB=testdb
ENV POSTGRES_USER=postgres
ENV POSTGRES_PASSWORD=postgres
ENV PGDATA=/var/lib/postgresql/data/pgdata
COPY init.sql /docker-entrypoint-initdb.d/init.sql