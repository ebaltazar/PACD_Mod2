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

XAMPP 3.0 (Servidor)

## Pasos para ejecutar notebook

### Instalación

```bash
# Clonar el repositorio
git clone https://github.com/ebaltazar/PACD_Mod2.git

# Entrar al directorio
cd "C:\tusuario\PACD_Mod2"

# Crear entorno virtual (ubicar en la carpeta del proyecto)
py -m venv venv_aereos

# No olvidar ACTIVAR el venv del proyecto.
venv_aereos\Scripts\activate #En Windows

# Instalar dependencias
pip install -r requirements.txt
```

Una vez realizado los comandos, se deberá descargar el dataset en la carpeta datos del proyecto.
