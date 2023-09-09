Для запуска контейнера используем команды:
docker build . -t postgres_image:latest
docker run -d -p 5432:5432 --name postgres_test postgres_image:latest