# Aplicação usando Python e Django 4

## Django Blog

Desenvolvida uma aplicação de blog.

## Tecnologias e práticas utilizadas
- Python
- Django 4
- SQLite
- Arquitetura MVT

## Funcionalidades
- Listagem, Detalhe, Cadastro e Edição de Posts

###

![alt text](https://raw.githubusercontent.com/samuel-oldra/DjangoBlog/main/README_IMGS/List.png)
![alt text](https://raw.githubusercontent.com/samuel-oldra/DjangoBlog/main/README_IMGS/Detail.png)
![alt text](https://raw.githubusercontent.com/samuel-oldra/DjangoBlog/main/README_IMGS/CreateEdit.png)

## Comandos

### pip
```
pip list --outdate
python -m pip install --upgrade pip
python -m pip install --upgrade setuptools
```

### virtualenv (windows)
```
python -m venv env
env\Scripts\activate.bat
env\Scripts\deactivate.bat
```

### Instalar bibliotecas, gravar/instalar requerimentos
```
(env) pip install Django

(env) pip freeze > requirements.txt
(env) pip install -r requirements.txt
```

### Criar projeto
```
(env) django-admin startproject mysite .
```

### Criar super user (Django Administration)
```
(env) python manage.py createsuperuser
```

### Criar apps
```
(env) python manage.py startapp blog
```

### Migrations
```
(env) python manage.py makemigrations
(env) python manage.py migrate
```

### Executar projeto
```
(env) python manage.py runserver
```