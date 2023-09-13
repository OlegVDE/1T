Для запуска контейнера используем команды:
docker build . -t postgres_image:latest
docker run -d -p 5432:5432 --name postgres_test postgres_image:latest

# Для доступа к базе исползуем
db_name = mydatabase
user_name = myuser
password = mypassword

# скрипт называем init.sql и ложим рядом с Dockerfile