
```bash
#!/bin/bash

# Crear un entorno virtual
echo "Creando entorno virtual..."
python -m venv env

# Activar el entorno virtual
echo "Activando entorno virtual..."
source env/Scripts/activate

# Activar el entorno virtual en Windows
venv\Scripts\activate

# Actualizar pip
echo "Actualizando pip..."
pip install --upgrade pip
```


```bash
#!/bin/bash
python -m venv entornovirtual
entornovirtual\Scripts\activate
pip install --upgrade pip
```

```bash
django-admin startproject manosalaobra
cd manosalaobra
python manage.py startapp usuarios
python manage.py startapp posts
python manage.py startapp comentarios
```



```bash
pip install django \
    psycopg2 \
    django-allauth \
    pillow \
    django-filter \
    drf-yasg \
    django-debug-toolbar \
    celery \
    redis \
    pytest-django \
    sentry-sdk \
    django-cors-headers \
    python-dotenv \
    markdown \
    python-slugify \
    django-ckeditor \
    djangorestframework 
```

```bash
pip install --upgrade pip
pip install django-cors-headers
pip install python-dotenv
pip install markdown
pip install python-slugify
pip install django-ckeditor
pip install 
```


```bash
pip freeze > requirements.txt

# Desinstalar una librería específica
pip uninstall djangorestframework -y

# Actualizar requirements.txt después de desinstalar
pip freeze > requirements.txt
```

# Instalar librerías
```bash
pip install django djangorestframework
```

# desinstalar librerías
```bash
pip freeze 
pip freeze > requirements.txt
```

# Instalar las dependencias:
```bash
pip install -r requirements.txt
```

# **Instala las dependencias**:
```bash
pip install -r requirements.txt
```

2. Crea una nueva aplicación llamada `clients`:
```shell
python manage.py startapp servicios
```

# Realizar las migraciones de la base de datos:
```bash
python manage.py migrate
```

# Migraciones
```bash
python manage.py makemigrations
python manage.py migrate
```

# Migraciones
```bash
py manage.py makemigrations
py manage.py migrate
```

5. **Crea un superusuario (opcional)**:
```bash
python manage.py createsuperuser
```

6. **Inicia el servidor de desarrollo**:
```bash
python manage.py runserver
py manage.py runserver 9000
```