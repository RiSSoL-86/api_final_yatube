Описание.
Данный проект позволяет осуществлять работу с приложением Yatube
по средством API на базе Django + Django REST framework.

Установка.
Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:
git clone git@github.com:RiSSoL-86/api_final_yatube.git
cd api_final_yatube

Cоздать и активировать виртуальное окружение:
python3 -m venv env
source venv/Scripts/activate

Установить зависимости из файла requirements.txt:
python3 -m pip install --upgrade pip
pip install -r requirements.txt

Выполнить миграции:
python3 manage.py migrate
Запустить проект:
python3 manage.py runserver

Перейти на локальный сервер:
http://127.0.0.1:8000/

Примеры запросов можно посмотреть по следующему адресу:
http://127.0.0.1:8000/redoc/
