ИСИС лабораторная 2

Создать образ:

docker build -t docker-image .

Запустить приложение:

docker run -ti -p 80:8080 docker-image
