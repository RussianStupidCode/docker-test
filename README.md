
![картинка](./readme_images/image.jpg)

## Сборка nginx
В директории task_one
```
docker build --tag ng .
docker run -d -p 80:80 --name my_nginx ng
```
перейти в http://127.0.0.1

## Сборка django-проекта
В директории task_two (проет брался [отсюда](https://github.com/RussianStupidCode/dj-hw-6) )
```
docker build --tag api .
docker run -d -p 80:80 --name django_project api
```
перейти в http://127.0.0.1/api/v1/
