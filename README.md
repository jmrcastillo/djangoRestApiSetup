

# Django Rest API Setup

## Installation Local

Clone the repo
```bash
git clone https://github.com/jmrcastillo/apps
cd apps
```

[Install Virtualenv & Pipenv](https://pipenv-fork.readthedocs.io/en/latest/install.html)

###### Install Dependencies using Pipenv

```bash
pipenv install
pipenv install --dev
```

###### Activate the virtualenv

```bash
pipenv shell
```

###### Run the Emkey API

```bash
./manage.py runserver --settings=apps.settings.local
```

###### Check this site to your browser
###### Endpoint Swagger

	- http://127.0.0.0.1:8000/

###### EndPoints Redoc

	- http://127.0.0.1:8000/redoc/

## License
[Mauro Castillo](https://github.com/jmrcastillo/djangoRestApiSetup)


