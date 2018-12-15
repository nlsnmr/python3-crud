# Python 3 CRUD

### A simple CRUD App With Python 3

__Python version__: 3.7.1  
__Django version__: 2.1.4  
__Template engine__: Jinja  
__Database__: Mysql  

![Preview](https://monosnap.com/image/3wBc0QSf0jOlrzgxoE5NPBaHQqGmul.png)

## Running this app Locally

First, clone the repository to your local machine:

```bash
git clone https://github.com/nlsnmr/python3-crud.git
```
Create enviroment && activate:
```bash
virtualenv . && . bin/activate
```

Install the requirements:
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
