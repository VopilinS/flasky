Установить Python 3.9.0
В командной строке ввести:
pip install virtualenv
Убедитесь, что ваш текущий каталог – flasky, а затем выполните следующую команду, чтобы создать виртуальную среду с именем venv:
virtualenv venv
venv\Scripts\activate
pip install flask
Переместить в каталог venv файл hello.py и каталог templates
pip install flask-bootstrap
pip install flask-moment
pip install flask-wtf
set FLASK_APP=hello.py
flask run
