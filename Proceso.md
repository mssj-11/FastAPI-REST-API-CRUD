#   Proceso de creación

##  ANACONDA:
[Descargar](https://www.anaconda.com/download-success)

##  Entorno virtual:
Creación de entorno virtual con el paquete de **ANACONDA** dentro de la carpeta creada `FastAPI-REST-API-CRUD` con el nombre opcional **FastAPI-REST-API-CRUD**.
```sh
conda create --name FastAPI-REST-API-CRUD python=3
```
### Activar el entorno virtual
```sh
conda activate FastAPI-REST-API-CRUD
```
### Desactivar el entorno virtual
```sh
conda deactivate
```

##  Instalación de FastAPI:
```sh
pip install fastapi
```
### Listar los paquetes
```sh
pip freeze > requeriments.txt
```

##  Iniciar App
```sh
python app.py
```
[Visualizar las rutas de la App]()


#   Con virtualENV
Instalar
```sh
pip install virtualenv
```
```sh
virtualenv env
```
Ingresar al entorno creado y Activarlo:
```sh
.\env\Scripts\activate
```
Desactivarlo:
```sh
deactivate
```

##  Instalación de FastAPI:
```sh
pip install fastapi
```
Listar los paquetes instalados
```sh
pip list
```
##  Instalación de Uvicorn:
Para iniciar el servidor de Python
```sh
pip install uvicorn
```
### Iniciando la App de Python
```sh
uvicorn app:app
```

##  Listando paquetes en un TXT:
```sh
python freeze > requeriments.txt
```
