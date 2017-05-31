
### 00. init

    echo "*.py[cod]" > .gitignore
    echo "Django==1.11.1" > requirements.txt

### 01. setup environment

    sudo pip install virtualenv
    virtualenv $HOME/11.1
    source $HOME/11.1/bin/activate
    pip install -r requirements.txt

### 02. creating the project 'clocking' and verify it

    django-admin startproject clocking
    cd clocking/
    # edit clocking/settings.py and add u'hello22-sdoro.c9users.io' to ALLOWED_HOSTS
    ./manage.py runserver $IP:$PORT
    # firefox https://hello22-sdoro.c9users.io
