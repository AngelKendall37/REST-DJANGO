# Instrucciones para el uso de la EndPoint de Django

Para utilizar correctamente la EndPoint de Django, sigue estos pasos:

1. Asegúrate de tener el proyecto Vue corriendo en tu máquina. Debes ejecutar el servidor Vue en uno de los siguientes puertos:

    ```python
    CORS_ALLOWED_ORIGINS = [
        "http://localhost:8080",  # El puerto de tu servidor Vue
        "http://127.0.0.1:8080",  # El puerto de tu servidor Vue
    ]
    ```

2. Si necesitas modificar la configuración de CORS, dirígete al archivo `settings.py` ubicado en la carpeta `djangorest`.

3. Es recomendable hacer uso de la virtualización para aislar las dependencias del proyecto. Para ello, sigue estos pasos:

    - Abre una terminal de comandos.
    - Activa el entorno virtual ejecutando el siguiente script:

        ```
        .\venv\Scripts\activate
        ```

Con estos pasos, deberías poder hacer uso correcto de la EndPoint de Django en conjunto con tu proyecto Vue.
