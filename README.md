# Project "YaMDb"
## Description
The YaMDb project collects user reviews of movies, music, and books.
The works themselves are not stored in YaMDb, you can't watch the movie here
or listen to music.


The works are divided into categories such as "Books", "Movies" and "Music".
Only the administrator can add works, categories and genres.

Grateful or indignant users leave text reviews for the works and rate them in the range from one to ten (an integer); the average works' rating is formed from user ratings.
A user can write only one review per work.
Users can write comments on reviews.

Only authenticated users can add reviews, comments and rate.

The list of endpoints is specified in the redoc:

When running on local config:
http://localhost:8000/redoc/

## Technologies in the project

- ### Django 3.2
- ### Django REST framework 3.12.4
- ### DRF Simple JWT 5.2.2

## Run instructions

Create a virtual environment:
```bash
python3.9 -m venv venv
```

Install requirements
```bash
pip install -r requirements.txt
```

Make migrations
```bash
python manage.py makemigrations
python manage.py migrate
```
Load data from csv
```bash
python manage.py load_data
```

## Team

- ### [Denis Panasenko](https://github.com/pandenic/)
- ### [Andrew Istratov](https://github.com/AI-Stratov/)
- ### [Valeriy Balashov](https://github.com/elValeron/)

<br>

# Проект "YaMDb"
## Описание
Проект YaMDb собирает отзывы пользователей на произведения. 
Сами произведения в YaMDb не хранятся, здесь нельзя посмотреть фильм 
или послушать музыку.


Произведения делятся на категории, такие как «Книги», «Фильмы», 
«Музыка».
Добавлять произведения, категории и жанры может только администратор.

Благодарные или возмущённые пользователи оставляют к произведениям 
текстовые отзывы и ставят произведению оценку в диапазоне от одного 
до десяти; из пользовательских оценок формируется 
усреднённая оценка произведения. 
На одно произведение пользователь может оставить только один отзыв.
Пользователи могут оставлять комментарии к отзывам.

Добавлять отзывы, комментарии и ставить оценки могут только аутентифицированные пользователи.

Список endpoints указан в redoc: 

При запуске на локальной конфигурации:
http://localhost:8000/redoc/

## Технологии в проекте

- ### Django 3.2
- ### Django REST framework 3.12.4
- ### DRF Simple JWT 5.2.2

## Иструкции по запуску

Создайте виртуальное окружение:
```bash
python3.9 -m venv venv
```

Установите requirements
```bash
pip install -r requirements.txt
```

Сделайте миграции
```bash
python manage.py makemigrations
python manage.py migrate
```
Загрузите данные из csv
```bash
python manage.py load_data
```

## Команда

- ### [Денис Панасенко](https://github.com/pandenic/)
- ### [Андрей Истратов](https://github.com/AI-Stratov/)
- ### [Валерий Балашов](https://github.com/elValeron/)
