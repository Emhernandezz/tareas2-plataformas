# Tarea 2 - Endpoint sencillo en Flask 

Se creó un endpoint con Flask que responde a solicitudes GET.

##  ¿Qué hace este proyecto?

El endpoint `/usuarios/api/v1/saludo`:

- Si NO recibe parámetros, devuelve: Lista de todos los usuarios.

- Si recibe el parámetro `id`, devuelve: El id del usuario es XXXX


## Tecnologías utilizadas

- Python 3.13.5
- Flask 3.1.1

## Cómo ejecutarlo

1. Clona el repositorio:
 ```bash
 git clone https://github.com/Emhernandezz/tareas2-plataformas.git
 cd tareas2-plataformas
```
2. Crea y activa el entorno virtual:
```bash
python -m venv env
.\env\Scripts\activate
```
3. Instala Flask:
```bash
pip install -r requirements.txt
```
4. Ejecuta la app:
```bash
python app.py
```
4. Abre en el navegador:
```bash
http://127.0.0.1:5000/usuarios/api/v1/saludo
http://127.0.0.1:5000/usuarios/api/v1/saludo?id=123
```

Tarea realizada por Emily Hernández✨