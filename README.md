# Django REST Framework

## Задание

Создайте REST API на базе Django REST Framework со следующими моделями:

* Студенты
  * Фамилия (строка до 50 символов)
  * Имя (строка до 50 символов)
  * Отчество (строка до 50 символов)
  * Номер студбилета (строка до 20 символов)
  * Учебная группа (внешний ключ со ссылкой на учебную группу)

* Учебная группа
  * Наименование (строка до 50 символов)
  * Год поступления (строка до 4 символов)

Во `viewset` не используйте `permission_classes`.

Убедитесь, что REST API работает с Curl или Postman.

## Работа с Django

Создание и активация виртуального окружения в Windows:

```bash
py -m venv venv
```

Активация виртуального окружения в командной строке Windows:

```bash
venv\scripts\activate.bat
```

Активация виртуального окружения в Powershell:

```bash
venv\scripts\activate.ps1
```

Активация виртуального окружения в Bash:

```bash
source venv/scripts/activate
```

Реструктуризация базы данных:

```bash
python manage.py makemigrations <имя приложения>
python manage.py migrate
```

Создание администратора для админки:

```bash
python manage.py createsuperuser
```

Запуск веб-сервера для разработки:

```bash
python manage.py runserver
```

## Указания

Если Powershell не запускает скрипты, запустите Powershell с правами администратора и выполните:

```bash
Get-ExecutionPolicy
Set-ExecutionPolicy Unrestricted
Get-ExecutionPolicy
```

## Ссылки

* https://www.djangoproject.com/
* https://www.django-rest-framework.org/
* https://django.fun/ru/
