# Creación de Entorno de Pruebas para Análisis de Vulnerabilidades Web
**Actividad - Unidad 3 – Vulnerabilidades Web**  

Para comenzar voy a 
+ Clonar el repositorio (antes yo he creado un directorio llamado unidad 3 y en su interior otro directorio más con el nombre de la tarea)
+ Entrar dentro de la carpeta del proyecto y hacer una copia del fichero sample.env en un fichero llamado .env
img1.png

A continuación entro en el archivo .env y veo que tiene un aspecto tal que el siguiente
img2.png

El siguiente paso ya es levantar el entorno haciendo uso del comando 
> docker compose up -d
(Tarda un poquillo)
img3.png


Y con el comando docker ps veo que efectivamente se han levantado los contenedores correctamente 
img4.png

A continuación accedo  verifico que phpmyadmin funciona correctamente accediendo en cualquier navegador de la máquina virtual a la url http://localhost:8080
img5.png

Y accedo a la pagina principal del entorno poniendo en cualquier navegador de la máquina virtual http://localhost
img6.png