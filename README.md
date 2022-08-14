# doc
- https://docs.djangoproject.com/en/4.0/topics/install/

```shell
pipenv install Django
# pipenv shell # opcional caso vc não queira digitar "pipenv run"
pipenv run python -m django --version
pipenv run django-admin startproject desafio21diaspython
cd desafio21diaspython
pipenv install
pipenv install Django
pipenv install mysqlclient
pipenv run python manage.py runserver
mysql
mysql> ALTER USER 'root'@'localhost' IDENTIFIED BY 'desaUfdiUo2531diaspy4827thon'; flush privileges;

mysql> CREATE USER 'root'@'%' IDENTIFIED WITH mysql_native_password BY 'desaUfdiUo2531diaspy4827thon';
mysql> GRANT ALL PRIVILEGES ON *.* TO 'root'@'%';
mysql> FLUSH PRIVILEGES;

mysql> create database desafio21dias_python_django;
mysql> exit
mysql -uroot -p'desaUfdiUo2531diaspy4827thon'
pipenv run python manage.py migrate
pipenv run python manage.py createsuperuser
pipenv run python manage.py runserver
pipenv run python manage.py startapp web

pipenv run python manage.py makemigrations
pipenv run python manage.py migrate

docker build -t didox/desafio21dias-django-python .
docker run -d -e USER -e PASSWORD -e DATABASE -e HOST -p 8000:8000 --name crud-python-login didox/desafio21dias-django-python



```

```mysql

CREATE USER 'root'@'%' IDENTIFIED WITH mysql_native_password BY 'desaUfdiUo2531diaspy4827thon';
GRANT ALL PRIVILEGES ON *.* TO 'root'@'%';
FLUSH PRIVILEGES;

```
