# Microblog
Flask mega tutorial: https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world

# Virtual env
```
python -m venv venv
source venv/bin/activate # Unix
venv\Scripts\activate # Windows
```

# Python packages
```
python -m pip install --upgrade pip
pip install flask
pip install python-dotenv
pip install flask-wtf
pip install flask-sqlalchemy
pip install flask-migrate
pip install flask-login
pip install flask-mail
pip install pyjwt
pip install flask-moment
pip freeze > requirements.txt
```

# Bootstrap package (optional)
```
pip install flask-bootstrap
```

# Database
```
flask db migrate -m "comment"
flask db upgrade
```

# Email server
```
python -m smtpd -n -c DebuggingServer localhost:8025
```

# Testing
```
python tests.py
```