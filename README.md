# TRABAJO PRÁCTICO - Segundo Módulo

Asignatura: Programación Avanzada para Ciencia de Datos

Profesor: Ing. Juan Carlos Cifuentes Durán

Alumno: Elmer Baltazar Llusco


## Dataset utilizado
Se eligió el siguiente dataset que contiene información de vuelos, pasajeros, rutas y aerolíneas en el país desde el año 2017.
Es provista por la Subsecretaría de Turismo

https://datos.gob.ar/dataset/turismo-conectividad-aerea/archivo/turismo_aab49234-28c9-48ab-a978-a83485139290

## Motor de base de datos
MySQL Workbench 8.0 (Cliente)
https://dev.mysql.com/downloads/workbench/?os=33 (usuario root)

XAMPP 3.0 (Servidor)
https://www.apachefriends.org/es/download.html (se debe activar módulo MySQL)

## Pasos para ejecutar notebook en Visual Studio Code + Jupyter

### Instalación

```bash
# Para abrir la terminal en VS Code, presionar Ctrl + ñ (ó + ')

#1. Clonar el repositorio
git clone https://github.com/ebaltazar/PACD_Mod2.git

#2. Entrar al directorio del proyecto
cd "C:\tusuario\..\PACD_Mod2"

#3. Crear entorno virtual (lo nombraremos venv_aereos)
py -m venv venv_aereos

#4. No olvidar ACTIVAR el venv del proyecto.
venv_aereos\Scripts\activate    #En Windows, para desactivarlo: deactivate

#5. Instalar dependencias
pip install -r requirements_vscode.txt

#6. Una vez abierta en la notebook, seleccionar el kernel venv_aereos(3.12.2) y ejecutarla
# Antes de hacerlo, se deberá descargar el dataset completo en la carpeta datos del proyecto.

```
