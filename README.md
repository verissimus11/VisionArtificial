# Detección de Objetos en Video con YOLOv5 usando Docker

Este proyecto utiliza YOLOv5 para detectar objetos en videos, con un contenedor Docker para facilitar su ejecución.

## Requisitos

- Tener instalado Docker en tu sistema.

---

## Instalación de Docker

### En Windows:
1. Descarga e instala Docker Desktop desde [https://www.docker.com/products/docker-desktop](https://www.docker.com/products/docker-desktop).
2. Durante la instalación, asegúrate de habilitar la integración con WSL 2 (Windows Subsystem for Linux).
3. Reinicia tu sistema si es necesario.
4. Abre Docker Desktop y verifica que Docker esté en ejecución.

### En macOS:
1. Descarga Docker Desktop desde [https://www.docker.com/products/docker-desktop](https://www.docker.com/products/docker-desktop).
2. Instala Docker Desktop como cualquier otra aplicación de macOS.
3. Abre Docker Desktop y verifica que Docker esté en ejecución.

### En Linux:
1. Abre un terminal y ejecuta los siguientes comandos:
   ```bash
   sudo apt-get update
   sudo apt-get install docker.io

### Abrir el CMD en la Carpeta del Proyecto

Para levantar el contenedor, es necesario abrir el terminal (CMD) en la carpeta donde está ubicado el proyecto. Sigue estos pasos:

1. **Navega a la carpeta del proyecto** en el Explorador de Archivos de Windows.
2. **Busca la barra de dirección** en la parte superior de la ventana.
3. Escribe `cmd` en la barra de dirección y presiona **Enter**.
   - Esto abrirá el terminal (CMD) directamente en la carpeta actual.
    !(cmd.png)
   
4. Una vez abierto el terminal, puedes ejecutar el siguiente comando:
   ```bash
   docker-compose up -d
