# Creación de Entorno de Pruebas para Análisis de Vulnerabilidades Web
**Actividad - Unidad 3 – Vulnerabilidades Web**  

## Objetivo
Configurar un entorno local LAMP mediante Docker Compose para disponer de un laboratorio seguro donde practicar vulnerabilidades web.

## Pasos realizados

### 1. Creación de la estructura de directorios
Con el uso de los comandos
```bash
mkdir Unidad3
cd Unidad3
mkdir CreacionEntornoPruebas
cd CreacionEntornoPruebas
```
Para tener el siguiente formato: 
Unidad3/
└──-CreacionEntornoPrueba/

---

### 2. Clonación del repositorio 
He clonado el repositorio y copiado el archivo de configuración .env pegando el siguiente bloque de comandos:
```bash
git clone https://github.com/sprintcube/docker-compose-lamp.git
cd docker-compose-lamp/
cp sample.env .env
```
![Paso 1 - Clonado y copia del .env](/images/img1.png)

---

### 3. Revisión del archivo .env
Compruebo el archivo .env y modifico contraseñas y usuarios para poder tener un mínimo de segurirdad

![Paso 2 - Vistazo al archivo .env](/images/img2.png)

---

### 4. Revisión del archivo .env
Levanto el entorno con el comando
```bash
docker compose up -d
```
![Paso 3 - Levantar el contenedor](/images/img3.png)

---

### 5. Verificación de contenedores
Verifico si el contendor se ha levantado correctamente poniendo lo siguiente en la línea de comandos 
```bash
docker ps
```
![Paso 4 - Verificación](/images/img4.png)

---

### 6. Acceso a phpMyAdmin
Abro cualquier navegador de la máquina virtual, en mi caso VirtualBox y pongo en la url http://localhost:8080 

![Paso 5 - phpMyAdmin](/images/img5.png)

---

### 7. Acceso a la página principal
En el mismo navegador pongo en la url http://localhost

![Paso 6 - Página principal LAMP](/images/img6.png)

---

## Conclusión
El entorno LAMP se ha configurado, iniciado y verificado correctamente. Tanto el servidor web como phpMyAdmin funcionan sin problemas
