# *Top movie, music, books* 📖🎥🎼
## Описание

**Top movie, music, books** - проект, который собирает **отзывы** пользователей на **произведения**. Сами произведения в **Top movie, music, books** не хранятся, здесь нельзя посмотреть фильм или послушать музыку.
Произведения делятся на **категории**, такие как «Книги», «Фильмы», «Музыка».
Благодарные или возмущённые пользователи оставляют к произведениям текстовые отзывы и ставят произведению оценку в диапазоне от одного до десяти (целое число); из пользовательских оценок формируется усреднённая оценка произведения — рейтинг (целое число). На одно произведение пользователь может оставить только один отзыв.
Пользователи могут оставлять комментарии к отзывам.

## 📝 **Ключевые собенности:**

🔸 Система регистрации при помощи JWT-токена

🔸 Пользовательские роли: **Аноним**, **Аутентифицированный пользователь**, **Модератор**, **Администратор**

🔸 Категории **categories** и жанры **genres** произведений

🔸 Возможность оставлять отзывы **reviews** с оценками и комментарии **comments** к ним пользователями **users**

## Технологический стек
[![Python](https://img.shields.io/badge/-Python-464646?style=flat&logo=Python&logoColor=56C0C0&color=cd5c5c)](https://www.python.org/)
[![Django REST Framework](https://img.shields.io/badge/-Django%20REST%20Framework-464646?style=flat&logo=Django%20REST%20Framework&logoColor=56C0C0&color=0095b6)](https://www.django-rest-framework.org/)
[![SQLite](https://img.shields.io/badge/-SQLite-464646?style=flat&logo=PostgreSQL&logoColor=56C0C0&color=cd5c5c)](https://www.sqlite.org/)

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/inrag3/api_yamdb.git
```

```
cd api_yamdb
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
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

### 😎 Авторы проекта:
#### Антонов Кирилл
```Github:```<https://github.com/Kirill-Antonov91>
#### Алехов Алексей
```Github:```<https://github.com/inrag3>
#### Густова Екатерина
```Github:```<https://github.com/Gustcat>
