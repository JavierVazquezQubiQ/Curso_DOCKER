# Resumen de comandos más utilizados Docker:

docker compose build --pull

Descargamos la imagen base.

------------------------------------------------------------------------------------------------------------------

docker compose -f setup-devel.yamls run --rm odoo

Descarga los modulos indicados en el repositorio y los añade en una carpeta para que se puedan utilizar más adelante en Odoo.

------------------------------------------------------------------------------------------------------------------

docker compose up

Lanzamos los contenedores para que podamos comenzar a usar nuestras aplicaciones.