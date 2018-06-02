# data-cleaning

Descargar la imagen de Docker:
- docker pull borbotonc/data-cleaning

Ejecutar el siguiente comando para levantar la notebook:
- docker run --rm  -p 8888:8888 -it borbotonc/data-cleaning  start-notebook.sh

Para corroborar que se esta trabajando con la rama más actualizada de la notebook:
- cd ~/work/data-cleaning 
- git pull

Requisitos del Docker:
- 4gb de memoria, sino la notebook va a devolver un error de kernel cuando se ejecutan las lineas de textacy
