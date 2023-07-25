# Установка
```shell
docker-compose up

docker-compose exec php-fpm composer install

docker-compose exec php-fpm php yii migrate/up --interactive=0
```

Зайти в бд 
Сервер:	mysql
Имя: пользователя app
Пароль: secret

В файл host прописать:
127.0.0.1 backend.test
127.0.0.1 frontend.test

Пути до файла:
Windows: C:\Windows\System32\drivers\etc\hosts
macOS/Linux: /etc/hosts

