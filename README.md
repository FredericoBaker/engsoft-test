## Setup

Instale as dependencias:

```sh
(env)$ pip install -r requirements.txt
```

Depois rode o servidor:
```sh
(env)$ cd ow_remedio
(env)$ python3 manage.py runserver
```
E navegue para `http://127.0.0.1:8000/`.
## Tests

To run the tests, `cd` into the directory where `manage.py` is:
```sh
(env)$ python manage.py test gc_app
```
