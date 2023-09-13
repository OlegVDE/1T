FROM postgres:latest
ENV POSTGRES_DB=mydatabase
ENV POSTGRES_USER=myuser
ENV POSTGRES_PASSWORD=mypassword
COPY init.sql /docker-entrypoint-initdb.d/init.sql
VOLUME postgres_data:/var/lib/postgresql/data
