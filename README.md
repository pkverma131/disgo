# disgo
**Install Pip**

`sudo pip3 install venv`

`pip3 --version`

**Install and create virtual environment**

`pip install --upgrade virtualenv`

`virtualenv -p /usr/bin/python3.8 disgo`

`source ../ENVS/disgo/bin/activate`

**Install Project Dependencies**

pip install django

pip install --upgrade pip

pip install django

pip install djangorestframework

pip install markdown

pip install django-filter

**Clone Project**

git clone https://github.com/pkverma131/disgo.git

**Install MySQL Server and Set root user password**

sudo apt-get update

sudo apt-get install mysql-server

sudo mysql_secure_installation

sudo mysql

ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password by 'disgo123';
mysql -u root -p

pip install pymysql 

**#import in __init__.py in project root ( same as setting.py )**

import pymysql

pymysql.install_as_MySQLdb()

python manage.py migrate

python manage.py createsuperuser

history > command_history.txt

history | cut -c 8- > command_history.txt
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