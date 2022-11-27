
# WillULean

WillULearn is an online flatform that helps you find a free online lectures.



## Installation

Follow this step to download and run the WillULearn in this directory:

```bash
$ git clone https://github.com/moebusChris/WillULearn
$ cd willulearn
$ virtualenv venv
$ source ./venv/bin/activate
$ pip install -r requirements
$ python manage.py migrate
$ python manage.py runserver

```
- Initial data supports 3 types of users for testing purposes:
    - User (username=user, password=letmein123)
    - Professor (username=professor, password=letmein123)
    - Admin (username=admin, password=letmein123)
    - Visit http://127.0.0.1:8000/
## Compatibility

- Python 3.9
- Django x.x
- SQLite, PostgreSQL, MySQL


## Notes

-
