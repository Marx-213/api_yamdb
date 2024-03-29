# Проект YaMDb

![Python](https://img.shields.io/badge/Python_3.7-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Python](https://img.shields.io/badge/django_2.2.9-%23092E20?style=for-the-badge&logo=django&logoColor=white)
![Python](https://img.shields.io/badge/drf_3.12.4-%23092E20?style=for-the-badge&logo=django&logoColor=white)
![Python](https://img.shields.io/badge/flake8_5.04-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Описание
Произведения в проекте YaMDb  делятся на следующие категории: «Книги», «Фильмы», «Музыка».

Администратор может расширить список категорий, а также удалять произведения, категории и жанры, назначать роли пользователям.

Каждому произведению может быть присвоен жанр из списка имеющихся. Только администратор имеет право добавлять новые жанры в этот список.

Зарегистрированные пользователи могут оставлять к произведениям текстовые отзывы и ставить оценку в диапазоне от одного до десяти произведениям, комментировать отзывы. Также они могут редактировать и удалять свои отзывы и комментарии, свои оценки произведений.

### Установка
Клонировать репозиторий и перейти в него в командной строке:
```
git clone https://github.com/yandex-praktikum/api_yamdb.git
``` 
Установить и активировать виртуальное окружение:
``` 
python3 -m venv env
source env/bin/activate
```
Установить зависимости из файла requirements.txt:
```
python3 -m pip install --upgrade pip
pip install -r requirements.txt
``` 
Выполнить миграции:
```
python3 manage.py migrate
```
Запустить проект:
```
python3 manage.py runserver
```
