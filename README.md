# Taller API Flask
API RESTful en Flask. Este es el código del taller para crear una API REST con Flask, se crea un CRUD básico y se almacenan los datos en base de datos utilizando el ORM SQLAlchemy. Permite registrar. eliminar y listar publicaciones

# Ejecución 
Para ejecutar la aplicación siga las siguientes instrucciones: 

## Crear un nuevo ambiente virtual
* ```$ python3 -m venv nuevo_ambiente```
* ```$ source nuevo_ambiente/bin/activate```

## Instalar las dependencias
* ```$ pip install flask``` 
* ```$ pip install flask-restful```
* ```$ pip install flask-marshmallow```
* ```$ pip install flask-sqlalchemy```
* ```$ pip install marshmallow-sqlalchemy```

## Configurar variables de entorno
* ```$ export FLASK_APP=app.py```
* ```$ export FLASK_DEBUG=1```
* ```$ export FLASK_ENV=development```

## Ejecutar
* ```$ flask run -h 0.0.0.0```
