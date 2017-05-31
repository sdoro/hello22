
### 00. init

    echo "*.py[cod]" > .gitignore
    echo "Django==1.11.1" > requirements.txt

### 01. setup environment

    sudo pip install virtualenv
    virtualenv $HOME/11.1
    source $HOME/11.1/bin/activate
    pip install -r requirements.txt
