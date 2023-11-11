# Гостевая книга
Изучения фреймворка symfony на основе официальной документакции и книги
> https://symfony.com/doc/6.2/the-fast-track/ru/index.html
## Вспомогательные команды
Запуск postgresql в системе linux
```
sudo systemctl start postgresql-16
```
Запуск pgsql через symfony
```
symfony run psql
```
Запуск pgsql через docker
```
docker-compose exec database psql app app
```
Создание дампа
```
symfony run pg_dump --data-only > dump.sql
```
Восстановление данных
```
symfony run psql < dump.sql
```