# Telegram Bot

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

## 📝Описание

Эта библиотека предоставляет Python асинхронный интерфейс для API Telegram Bot. Он совместим с версиями ```Python 3.9+```.

Помимо реализации API, эта библиотека включает несколько удобных методов и сокращений, а также ряд высокоуровневых классов, которые упрощают разработку ботов.

## ✈Установка

1. Вы можете установить (обновить) ```python-telegram-bot``` с помощью:

    ```bash
    $ pip install python-telegram-bot --upgrade
    ```
2. Вы также можете установить ```python-telegram-bot``` из источника:

    ```bash
    $ git clone https://github.com/python-telegram-bot/python-telegram-bot
    $ cd python-telegram-bot
    $ pip install build
    $ python -m build
    ```

## 💻 Использование

Для публикации бота вы можете использовать бесплатный хостинг https://containers.back4app.com/. В корневой папке вашего приложения необходимо
создать Dockerfile для автоматического создания контейнера при запуске на хостинге.\
Пример ```Dockerfile```:
```
FROM python:3.9

WORKDIR /usr/src/app/

COPY . /usr/src/app/

RUN pip install pytelegrambotapi

CMD ["python", "main.py"]
```

## 📡Связаться со мной
* 📞 Телефон: +7 967 284 46 17
* 📧 Email: cerakuzz@mail.ru

