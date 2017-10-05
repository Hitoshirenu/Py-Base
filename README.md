# Py-Base
Python as a Data base instead of a traditional one with better fidelity.

## Pre-requisites

* [Python3](https://www.python.org/downloads/)
* [pip3](https://bootstrap.pypa.io/get-pip.py)
* [bs4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
* [requests](http://docs.python-requests.org/en/master/)
* [virtualenv](http://docs.python-guide.org/en/latest/dev/virtualenvs/)
* [gspread](http://gspread.readthedocs.io/en/latest/)

* Install virtualenv
  * `pip install virtualenv`

  * `mkdir Py-Base` or `cd /Path/to/the/repo`

  * `virtualenv Py-Base`

  * `source ./bin/activate`
    * Console prompt should be like `(Py-Base) machine-name@user-name$` 

###Tip:

`$run virtualenv freeze > requirements.txt`
    * [To create a list of all the installed modules]
    
`$ pip freeze > requirements.txt`
    * [To install from a reqirements.txt]

 
## Testing installation

* `$which python`

* `$which pip`

* `$which python3`

* `$which pip3`

* `$ python`

```python
>>> import requests
>>> import bs4
>>> import gspread
>>>
```
