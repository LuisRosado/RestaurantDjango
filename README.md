# Little Lemon Restaurant Web App

Esta es una aplicación web para un restaurante llamada "Little Lemon", creada con el framework Django.

## Descripción

La aplicación permite a los usuarios:
- Ver el menú del restaurante.
- Hacer reservas.
- Obtener información sobre el restaurante.

Los administradores pueden gestionar los elementos del menú a través de la interfaz de administración de Django.

## Estructura del Proyecto

- **urls.py**: Configura las rutas URL de la aplicación principal.
- **views.py**: Define las vistas para la aplicación `restaurant`.
- **models.py**: Define los modelos de datos para la aplicación `restaurant`.
- **wsgi.py**: Configuración WSGI para el despliegue de la aplicación Django.
- **admin.py**: Registra los modelos en el sitio de administración de Django.

## Instalación

1. Clona el repositorio:
    ```bash
    git clone (https://github.com/LuisRosado/RestaurantDjango/tree/main)
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd littlelemon
    ```
3. Crea y activa un entorno virtual:
    ```bash
    python -m venv env
    .\env\Scripts\activate  # En Windows
    ```
4. Instala las dependencias:
    ```bash
    pip install -r requirements.txt
    ```
5. Realiza las migraciones de la base de datos:
    ```bash
    python manage.py migrate
    ```
6. Inicia el servidor de desarrollo:
    ```bash
    python manage.py runserver
    ```

## Uso

- Accede a la aplicación en tu navegador en `http://127.0.0.1:8000/`.
- Para acceder a la interfaz de administración, ve a `http://127.0.0.1:8000/admin/` y usa las credenciales de administrador.

## Contribución

Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -am 'Añadir nueva funcionalidad'`).
4. Sube tus cambios a tu fork (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.
