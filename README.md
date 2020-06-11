# Aplicação usando Python e Django 4.1

## Django Blog

Desenvolvida uma aplicação de blog.

## Tecnologias e práticas utilizadas
- Python 3.8
- Django 4.1
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
pip install --upgrade pip setuptools Django ...
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
(env) python manage.py createsuperuser (admin/admin)
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