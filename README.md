# ca.berlin.freifunk.net

## Development

Install and use virtualenv with:

```
virtualenv env
. env/bin/activate
```

Install dependencies with pip:

```
pip install -r requirements.txt
```


Setup the database

Open a python terminal and run
```
from app import db
db.create_all()
```

Note that the default path for the database is in `/tmp` so you will lose your data when rebooting.

Run the application
```
python3 manage.py runserver
```

All development should be done in Python 3.
