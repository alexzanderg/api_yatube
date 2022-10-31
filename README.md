# API Yatube

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![](https://img.shields.io/badge/django%20rest-ff1709?style=for-the-badge&logo=django&logoColor=white)
![](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=green)
![](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white)

API Yatube - API для веб-приложения Yatube и документацией к нему.

Возможности API:
- регистрация пользователей
- получение токенов для доступа
- публикация записей
- комментирование записей
- подписка на других пользователей

## Установка

Клонировать репозиторий и перейти в него в командной строке:
```
git clone git@github.com:alexzanderg/api_yatube.git
```
```
cd api_yatube
```
Cоздать и активировать виртуальное окружение:
```
python3 -m venv env
source env/bin/activate
```

Установить зависимости из файла requirements.txt:
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
## Примеры
Добавить примеры GET, POST запросов