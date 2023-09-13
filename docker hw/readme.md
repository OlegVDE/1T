# Для запуска контейнера качаем и в папке с файлом docker-compose.yml вводим команду
docker-compose up -d

# Для доступа к базе исползуем
db_name = testdb  

user_name = postgres  

password = postgres  


# скрипт называем init.sql и ложим рядом с Dockerfile в папку postgres
# скрипт pythona  ложим в папку python_app