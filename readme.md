# A simple to-do list webapp as an excuse to practice Test Driven Development
I wanted to brush up on my Python as well as practice my Test-Driven Development skills. Luckily I found a book that covered both. ![Book Cover](https://images-na.ssl-images-amazon.com/images/I/51u3%2B7xekbL._SX379_BO1,204,203,200_.jpg "Test-Driven Development with Python")

# Frequently used commands during development
## updating pip
```
$ python -m pip install --upgrade pip
```

## Setting up virtualenv
```
python -m venv virtualenv
```

## Turning virtualenv back on
```
source virtualenv/Scripts/activate
```

## Turning virtualenv OFF
```
deactivate
```

## running the server 
```
python manage.py runserver
```

## Running Tests
### Functional(end-to-end) and unit tests
```
python manage.py test 
```
### Unit tests only
```
python manage.py test lists
```
### Functional(end-to-end) tests only
```
python manage.py test functional_tests
```




## Git Aliases
This is unrelated to this project but I like to use a few aliases in Git to make reviewing my history more compact and easier on the eyes. A few others are included for laziness as well.

`git config --global alias.hist "log --pretty=format: '%ad | %s%d [%an]' --graph --date=short`
`git config --global alias.st status`
`git config --global alias.br branch`

### Now you can type:
`git hist` --- to see a **compact** commit history

`git st` --- to see the current **status** of changes instead of `git status`

`git br` --- to see/change current **branch**
