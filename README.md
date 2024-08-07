Разработка Системы Управления Задачами

Endpoints:

1

URL: /signup

Метод: Post

Доступно всем

Описание: Регистрация пользователя


2

URL: /signin

Метод: Post

Доступно всем

Описание: Вход пользователя через username и password

3

URL: /create-task

Метод: Post

Доступно авторизированным

Описание: Создание задачи

4

URL: /update-task/{id}

Метод: Post

Доступно авторизированным

Описание: Обновление задачи

5

URL: /check-task/{id}

Метод: Get

Доступно авторизированным

Описание: Просмотр задачи


6

URL: /delete-task/{id}

Метод: Post

Доступно авторизированным

Описание: Удаление задачи


7
URL: [/task/{id}/comment](src/main/java/app/controllers/TaskController.java)

Метод: Post

Доступно авторизированным

Описание: Добавление комментраия к задаче
