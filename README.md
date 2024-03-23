# Учебный проект по Django 4.2.6
### Создание веб приложения онлайн магазина
Данный проект направлен на углубленное изучение фреймворка Django и представляет из себя веб-приложения онлайн магазина аналога авито
#### Особенности и функционал:
- Авторизация и регистрация пользователя (подтверждение по электронной почте, капча и восстановление пароля при помощи электронной почты)
- Размещение объявления пользователем
- Переход на страницу пользователя, разместившего объявление
- Фильтрация обьявлений на главной странице по заголовку
- Админ-панель
- Профиль с возможностью установки аватара и смены данных
#### Используемые технологии
 Фронтенд: HTML,CSS,JS (bootstrap)
 Бэкэнд: python (Django)
 База данных: PostgreSql
 Капча: https://www.google.com/recaptcha/about/
#### Установка 
1. Клонируйте репозиторий git clone https://github.com/Easy-ch/portfolio.git
2. Установите необходимые библиотеки pip install -r requirements.txt
3. Установите pgAdmin и создайте базу данных
4. Установите подключение к базе данных в файле settings.py
5. Выполните миграции к базе данных при помощи python manage.py makemigrations и python manage.py migrate
6. Запустите приложение при помощи команды python manage.py runserver и перейдите по ссылке после запуска сервера
### Данный проект создан исключительно в целях изучения архитектуры и возможности фреймворка для python Django

