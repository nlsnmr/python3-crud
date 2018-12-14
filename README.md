# python3-CRUD

## Running this app Locally

First, clone the repository to your local machine:

```bash
git clone https://github.com/nlsnmr/python3-crud.git
```
After enviroment activation, install the requirements:

```bash
pip install -r requirements.txt
```

Setup the local configurations:

```bash
cp .env.example .env
```

Create the database:

```bash
python manage.py migrate
```

Finally, run the development server:

```bash
python manage.py runserver
```

The app will be available at **127.0.0.1:8000**.
