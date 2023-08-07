# Kittygram

### Ссылка на сайт: https://mypussycats.ddns.net

## Описание

Kittygram - социальная сеть, созданная для загрузки фото с любимыми котиками. На сайте возможна регистрация пользователей, просмотр публикации других пользователей, а также загрузка фото своих любимцев.

## Технологии

Python, Django, React, WEB-сервер Nginix, WSGI-сервер Gunicorn.


## Запуск проекта

#### Клонировать репозиторий

```
git@github.com:vovan46rus/infra_sprint1.git
```

#### Активировать виртуальное окружение и установить зависимости для бэкэнд-приложения Django

```
python3 -m venv venv
```

```
source/bin/activate/
```

```
pip install -r requirements.txt
```

```
python3 manage.py migrate
```

#### Установить зависимости для фронтенд-приложения React

```
npm i
```

```
npm run build
```

#### Перезапустить daemon

```
sudo systemctl daemon-reload
```

```
sudo systemctl reload nginx
```

