Entregables
1. Código Fuente del Proyecto
ChatApp: Carpeta raíz del proyecto Django.
Estructura organizada y comentada.
Archivos relevantes: settings.py, urls.py, asgi.py, consumers.py, routing.py, models.py, views.py, y otros archivos pertinentes.
2. Documentación
2.1 Instrucciones para Configurar y Ejecutar el Proyecto
Entorno Virtual:

Crear un entorno virtual: python -m venv myenv.
Activar el entorno virtual:
Windows: myenv\Scripts\activate.
Linux/Mac: source myenv/bin/activate.
Instalación de Dependencias:

Instalar Django y Channels: pip install django channels daphne.
Configuración del Proyecto:

Crear el proyecto Django: django-admin startproject ChatApp.
Crear la app chat: python manage.py startapp chat.
Configurar archivos como settings.py, routing.py, consumers.py, asgi.py, y urls.py.
Migraciones y Ejecución:

Aplicar migraciones: python manage.py makemigrations y python manage.py migrate.
Iniciar el servidor de desarrollo: python manage.py runserver.
2.2 Descripción de la Estructura del Proyecto y Decisiones de Diseño Importantes
Estructura del Proyecto:

Explicación de la organización de carpetas y archivos.
Detalles sobre los componentes clave y su función en el proyecto.
Decisiones de Diseño:

Descripción del modelo de datos (models.py) y su relación con la lógica de las vistas.
Justificación de la implementación de funcionalidades clave, como la gestión de WebSocket y la configuración de Channels.
Explicación de la lógica y funcionamiento del consumidor de WebSocket y su integración en la aplicación.

