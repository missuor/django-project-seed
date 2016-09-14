### Django Project Seed

#### Dev Env Building

**dep**(Linux)
+ sudo apt-get install python-dev
+ sudo apt-get install libmysqld-dev
+ sudo apt-get install python-pip
+ sudo pip install virtualenvwrapper
+ vim ~/.bashrc (add following line to the end of this file)

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
+ cd /path/to/django-project-seed
+ python manage.py migrate

**run**
+ python manage.py runserver
