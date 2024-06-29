![Kittygram workflow](https://github.com/Prospero6666/kittygram_final/actions/workflows/main.yml/badge.svg)

#  Kittygram — это платформа для обмена фотографиями, специально созданная для любителей кошек

## Описание проекта

Kittygram – это готовое решение с фронтендом и бэкендом, а также поддержкой API. Сервис позволяет пользователям регистрироваться и делиться очаровательными снимками своих питомцев, просматривать фото других пользователей и находить вдохновение в мире кошачьих приключений. Kittygram предоставляет удобные инструменты для загрузки изображений, выбора цветов и добавления уникальных достижений питомцев.

## Стек

### Python, Django, PostgreSQL, SQLite, Docker, Ubuntu и Nginx

## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:
```
git clone git@github.com:Prospero6666/kittygram_final.git
```
```
cd kittygram_final
```
Cоздать и активировать виртуальное окружение:
```
Для Windows:
python -m venv env
source venv/Script/activate

Для Linux/MacOS:
python3 -m venv env
source venv/bin/activate
```
Установить зависимости из файла requirements.txt:
```
Для Windows:
python -m pip install --upgrade pip
pip install -r requirements.txt

Для Linux/MacOS:
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```
Заполнить .env file:
```
# Файл .env
POSTGRES_USER=<your_user_name>
POSTGRES_PASSWORD=<your_password>
POSTGRES_DB=<your_db_name>
DB_HOST=<db_name>
DB_PORT=5432
SECRET_KEY=<your_secret_key>
ALLOWED_HOSTS=<your_allowed_hosts>
```
### Автор
Bakhtiyar Kayupov