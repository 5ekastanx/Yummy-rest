# 🍷Yummy Restaurant Project

## 🖇️Описание

Yummy - это проект для управления данными ресторана, разработанный с использованием Django и Django REST Framework (DRF). Проект включает админ панель, где можно изменять данные, такие как посты, меню, мероприятия и многое другое. Этот проект идеально подходит для бекенд разработчиков, которые хотят создать и управлять данными ресторана.

## ⬇️Установка
 
### Клонирование репозитория 🦄

```bash
git clone https://github.com/nasirovx/Yummy-Restaurant.git
cd Yummy-Restaurant
Настройка виртуального окружения
Создайте и активируйте виртуальное окружение:

python -m venv venv
source venv/bin/activate  # для Windows: venv\Scripts\activate
Установка зависимостей
Установите все необходимые зависимости:

pip install -r requirements.txt
Применение миграций
Примените миграции для создания базы данных:

python manage.py migrate
Создание суперпользователя
Создайте суперпользователя для доступа к админ панели:

python manage.py createsuperuser
Запуск сервера
Запустите сервер разработки:

python manage.py runserver
Откройте браузер и перейдите по адресу http://127.0.0.1:8000/admin, чтобы войти в админ панель.

Использование
Через админ панель можно изменять все данные, такие как посты, меню, мероприятия и многое другое. Админ панель доступна по адресу http://127.0.0.1:8000/admin.
