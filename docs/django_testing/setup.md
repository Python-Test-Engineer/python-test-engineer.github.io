## Instuctions

- cd TEST_SUITE_05_DJANGO.
- creater virtual env `python -m venv venv`.
- pip install -r requirents.txt
- run `playwright install` to load in playwright browsers.
- in one terminal run `python manage.py runserver`.
- For unittests run `python manage.py test`
- in another run `python -m pytest -v` or `python -m pytest -v --headed` if using  playwright and you want to see browsers. Sometimes this may not work so you will need to add the headless=False to the test.
- DB has had migrations. superuser: admin password
- authuser uses a Custom User model so that login defaults to email and password. This can be removed so that the User model is used. super user is `admin@test.com` and `password`.
- pytest-sugar added for fancier terminal output
- PyBoxen used for fancy console output. Examples are in the orm app.
- django-extensions used in orm app so that we can run scripts in a py file rather than in shell. See `orm/_NOTES.md` for more details.

## Alternative

*If one is not using requirements.txt one would need to install:*

- django
- django-extensions for the utuilities used in orm.
- pytest, pytest-django, pytest-cov.
- playwright for browser based testing (an then run `playrwight install` to load browsers).
- pytest-sugar for nicer output format of tests.
- pyboxen for fancy console output used in orm.
- requests for order app.