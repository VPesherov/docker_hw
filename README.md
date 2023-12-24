Первая часть и первый докер находиться в папке homework-nginx
Вот так его можно запустить

docker build -t my-nginx .
docker run --name my-nginx-server -d -p 8081:80 my-nginx

и по локалке через порт 8081 можно подключаться

Второй докер находиться в папке netology_CRUD_homework

Собираю через 

docker build -f Dockerfile -t my_django_hw:v1 .

Запускаю через

docker run my_django_hw:v1

Пока не работает второй докер, нужна помощь)