# updating pip
```
$ python -m pip install --upgrade pip
```

# Setting up virtualenv
```
python -m venv virtualenv
```

# Turning virtualenv back on
```
source virtualenv/Scripts/activate
```

# Turning virtualenv OFF
```
deactivate
```

# running the server 
```
python manage.py runserver
```

# running tests
```python
python manage.py test # functional(end-to-end) and unit tests
python manage.py test lists # unit tests only
python manage.py test functional_tests# functional(end-to-end) tests only
```


# see git commit log
```
git log --oneline
```