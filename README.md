### Django Project Seed

#### Dev Env Building

**dep**(Linux)
+ sudo apt-get install python-dev
+ sudo apt-get install libmysqld-dev
+ sudo apt-get install python-pip
+ sudo pip install virtualenvwrapper
+ vim ~/.bashrc (末尾加上下面这行)

`source /usr/local/bin/virtualenvwrapper.sh`
+ source ~/.bashrc

**dep**(Windows)

make sure Python2.7.10+ installed (pip and setuptools included)
+ pip install virtualenvwrapper-win


**env**
+ mkvirtualenv sas
+ workon sas
+ cd /path/to/oe-sas
+ pip install -r requirements.txt

**init**
+ cd /path/to/oe-sas
+ python manage.py migrate

**run**
+ python manage.py runserver
