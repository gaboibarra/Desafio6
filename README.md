# 📚 Desafío 6 - Ansible Proyecto Modular

## 🎯 Objetivo

El objetivo de este desafío es validar el entorno de desarrollo y realizar una modularización del proyecto de configuración utilizando Ansible. El objetivo principal es estructurar el proyecto para reducir líneas de código, reutilizar variables y mover la lógica a archivos específicos.

## 📝 Escenario

Nuestro equipo inició un nuevo sprint con la tarea de modularizar el proyecto de configuration manager utilizando Ansible. El proyecto permite instalar y desplegar un sitio web en hosts Ubuntu agregados a demanda. El desafío consiste en estructurar el proyecto para reutilizar código previamente desarrollado.

## 🚀 Tecnologías Utilizadas

- 🐧 **WSL2 (Windows Subsystem for Linux 2)** - Entorno Linux en Windows
- 🛠️ **Ansible** - Configuración como código
- 💻 **Ubuntu** - Sistema operativo de destino
- 🌐 **Apache** - Servidor web
- 📂 **Git** - Control de versiones
- 🗃️ **GitHub** - Repositorio del proyecto

El proyecto se estructura en roles para lograr una modularización efectiva:

- **Common**: Instalación de paquetes esenciales.
- **Webserver**: Configuración de Apache y despliegue de archivos web.

Para este desafío voy a utilizar mi maquina con Windows en vista de que ansible no se ejecuta en Windows voy a usar WSL2 
