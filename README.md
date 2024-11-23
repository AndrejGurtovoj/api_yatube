# API социальной сети "Yatube"

## Описание проекта
Это социальная сеть для блогеров. В которой реализована авторизация на Django, работа с Базами Данных, создание индивидуальных страниц пользователей. Создание постов, их оценка и возможность добавить комментарии.

Позволяет делать запросы к моделям проекта: Посты, Группы, Комментарии, Подписки. Поддерживает методы GET, POST, PUT, PATCH, DELETE Предоставляет данные в формате JSON

### Технологии:
- django==2.2.16
- djangorestframework==3.12.4
- requests==2.26.0
- Pillow==8.3.1
- 
### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/AndrejGurtovoj/api_yatube.git
```

Cоздать и активировать виртуальное окружение:

Windows
```
python -m venv venv
source venv/Scripts/activate
```
Linux/macOS
```
python3 -m venv venv
source venv/bin/activate
```

Обновить PIP

Windows
```
python -m pip install --upgrade pip
```
Linux/macOS
```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

Windows
```
python manage.py makemigrations
python manage.py migrate
```

Linux/macOS
```
python3 manage.py makemigrations
python3 manage.py migrate
```

Запустить проект:

Windows
```
python manage.py runserver
```

Linux/macOS
```
python3 manage.py runserver
```
