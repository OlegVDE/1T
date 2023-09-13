FROM postgres:latest
ENV POSTGRES_DB=testdb
ENV POSTGRES_USER=postgres
ENV POSTGRES_PASSWORD=postgres
COPY init.sql /docker-entrypoint-initdb.d/init.sql
VOLUME postgres_data:/var/lib/postgresql/data
