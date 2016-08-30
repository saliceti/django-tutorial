Polling app from the [Django tutorial](https://docs.djangoproject.com/en/1.10/intro/tutorial01/).

### Run

```bash
$ pip install -r requirements.txt
...
$ python manage.py migrate
...
$ python manage.py runserver
...
```

* Access http://127.0.0.1:8000/admin for the admin app
* Access http://127.0.0.1:8000/polls for the polls app

### Notes

* It runs by default using `sqlite` as a backend.
* Tested with Python 3.4.4 and 3.5.1
* The default admin user is : `admin/abcdefgh`
