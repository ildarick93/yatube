# Yatube
Социальная сеть с системой публикации записей пользователей. Добавлена возможность комментирования, подписки. Регистрация реализована с верификацией данных, сменой и восстановлением пароля через почту. Используется пагинация постов и кэширование. Написаны тесты, проверяющие работу сервиса.

## Стек технологий
* Python 3.9.1 
* Django 2.2
* SQLite
* Unittest
* Git

## Установка проекта
Установить актуальную версию Python3 с официального сайта, если он не установлен:
https://www.python.org

Выполните команду:
```python
git clone https://github.com/ildarick93/Yatube
```
Перейдите в репозиторий:
```python
cd Yatube
```
В корневой папке проекта создайте виртуальную среду python:
```python
python -m venv venv
```
Активируйте виртуальную среду командой:
Windows:
```python
venv\Scripts\activate.bat
```
Linux или macOS:
```python
source venv/bin/activate
```
Установите необходимые зависимости с помощью pip:
```python
pip install -r requirements.txt
```
При необходимости обновления зависимостей используйте команду:
```python
python -m pip install —upgrade pip
```
