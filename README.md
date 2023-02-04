# yatube_project

## Описание проекта: 

•	**Назначение:** 

Четвертая версия социальной сети для публикации личных дневников. 

•	**Реализованный функционал:** 

1. Тестирование моделей
2. Тестирование URLs
3. Проверка namespace:name и шаблонов
4. Тестирование контекста
5. Дополнительная проверка при создании поста
6. Тестирование Forms

•	**Цель выполнения проекта:**

Практика использования Unittest

•	**Стек:**

Python 3.7, Django 2.2.19, SQLite, pytest, Unittest.

## Инструкция по развёртыванию проекта

•	**Клонируйте репозиторий:**

```csharp 
git clone git@github.com:antsakharov/hw04_test.git
```

•	**Установите и активируйте виртуальное окружение:**

**для Linux и MacOS**

```csharp 
python3 -m venv venv
```

**для Windows**

```csharp 
python -m venv venv
```

```csharp 
source venv/bin/activate
```

```csharp 
source venv/Scripts/activate
```

•	**Установите зависимости из файла requirements.txt:**

```csharp 
pip install -r requirements.txt
```
•	**Создайте и выполните миграции:**

```csharp 
python manage.py makemigrations
```

```csharp 
python manage.py migrate
```

