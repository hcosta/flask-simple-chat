# Flask simple chat

Clonado y modificado de https://github.com/samhita-alla/flask-chat-app-article 😁.

```
pip install -r requirements.txt
```

```
python server.py
``````

Abrir http://localhost:5000 y poco más.

## Deploy en Heroku

Requisitos:

* Chocolatey
* Cuenta en Heroku

En el directorio de la app clonada con git:

```
heroku login
``````

```
heroku create
``````

```
heroku push heroku master
``````

Y se abre la URL pero en versión http (no segura):

http://mysterious-refuge-34524.herokuapp.com/