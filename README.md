# RustamRuzibaev_microservices
RustamRuzibaev microservices repository
## Технология контейнеризации. контейнеризации. Введение в Docker Введение в Docker
1. Добавлен Dockerfile для создания образа reddit
2. Добавлены файлы, необходимые для запуска Dockerfile
3. Образ reddit загружен в dockerhub (ramondomc/otus-reddit)
4. На основе образа reddit были запущены конейнеры как в удаленном, так и в локальном окружении
5. Проверена работоспособность docker-контейнеров на баазе образа reddit
## Docker-образы Микросервисы
1. Приложение было разбито на 3 части (post-py, comment, ui)
2. Для каждого компонента описан Dockerfile
3. Добавлена bridge-сеть reddit для приложения
4. Был создан и подключен volume к контейнеру с базой данных для хранения данных.
