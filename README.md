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
pip install flask-cors
pip freeze > requirements.txt
pip install -r requirements.txt
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

# .flaskenv example
```
FLASK_APP=microblog.py
FLASK_ENV=development
FLASK_DEBUG=1
```

# .env example
```
SECRET_KEY=a-really-long-and-unique-key-that-nobody-knows
MAIL_SERVER=localhost
MAIL_PORT=8025
```

# Testing
```
python tests.py
```

# Bootstrap package (optional)
```
pip install flask-bootstrap
```
