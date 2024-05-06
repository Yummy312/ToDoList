ToDo приложение - это простое веб-приложение для управления задачами. Пользователи могут создавать, просматривать, обновлять и удалять задачи.

## Установка

1. Клонируйте репозиторий на ваш локальный компьютер:
```shell
git clone https://github.com/Yummy312/ToDoList.git
```

2. Установите зависимости:

```shell
pip install -r requirements.txt
```

3. Примените миграции:

```shell
python manage.py makemigrations
```
затем

```shell
python manage.py migrate
```


## Использование

1. Запустите сервер разработки:
```shell
python manage.py runserver
```

2. Откройте ваш веб-браузер и перейдите по адресу:
http://localhost:8000/