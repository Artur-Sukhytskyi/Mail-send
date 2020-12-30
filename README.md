# Mail send

В данном задании нужно реализовать сервис, который будет отправлять email через заданное количество секунд. Для этого мы делаем две страницы. На первой странице вводим параметры (текст email и через какое количество секунд его отправить). На второй странице показываем последние десять писем, которые мы поставили в план (и те, что должны отправиться в будущем, и уже отправленные).

Данный сервис должен быть реализован с применением многопоточности: после того, как письмо создано, должен создаться тред, который должен быть закрыт в какой-то момент.

Чтобы запустить его локально, вам необходимо:
1. Скопировать этот репозиторий;
2. Перейти в папку с ним и создать вртуальную среду: python -m venv venv
3. Активировать среду: cd venv\Scripts activate.bat;
4. Установить необходимые зависимости: pip install -r requirements.txt;
5. Запустить сервер: python manage.py runserver:

In this task, you need to implement a service that will send an email after a specified number of seconds. For this we make two pages. On the first page, enter the parameters (the email text and how many seconds it will take to send it). On the second page, we show the last ten letters that we put in the plan (and those that should go in the future, and those already sent).

This service should be implemented using multithreading: after the letter is created, a thread should be created, which should be closed at some point.

To run it locally, you need:
1. Copy this repository;
2. Go to the folder with it and create a virtual environment: python -m venv venv
3. Activate the environment: cd venv \ Scripts activate.bat;
4. Install the required dependencies: pip install -r requirements.txt;
5. Start the server: python manage.py runserver:
