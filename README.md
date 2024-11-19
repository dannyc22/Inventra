# Proyecto Integrado de Aula

## Integrantes
- **Andrés Castro**
- **Daniel Chacón**
- **Wendy Guio**

## Descripción del Proyecto
Este proyecto ha sido desarrollado en Django y está diseñado para la gestión de inventarios de una tienda. Incluye funcionalidades como agregar, editar y eliminar productos, gestionar clientes y registrar ventas.

## Requisitos de Instalación

1. **Python** (3.x recomendado)
2. **Django** (4.x recomendado, pero puede ser compatible con otras versiones)

## Pasos para Configurar el Proyecto

1. **Clonar el Repositorio**

   Clona el repositorio en tu máquina local:

   ```bash
   git clone https://github.com/usuario/proyecto-inventario.git
   cd proyecto-inventario
Crear y Activar un Entorno Virtual

Para evitar conflictos de dependencias, crea un entorno virtual:

bash
Copiar código
python3 -m venv env
source env/bin/activate   # En MacOS/Linux
env\Scripts\activate      # En Windows
Instalar Django

Instala Django usando pip:

bash
Copiar código
pip install django
Configurar el Proyecto Django

Dentro de la carpeta principal del proyecto, asegúrate de realizar las migraciones necesarias para crear la estructura de la base de datos:

bash
Copiar código
python3 manage.py migrate
Iniciar el Servidor

Para ejecutar el proyecto en un entorno de desarrollo, inicia el servidor de Django:

bash
Copiar código
python3 manage.py runserver
