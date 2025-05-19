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

### 📂 Organización de Roles
```
roles/
├── common/
│   ├── tasks/
│   ├── vars/
│   └── templates/
└── webserver/
    ├── tasks/
    ├── vars/
    └── templates/
```

Para este desafío voy a utilizar mi maquina con Windows en vista de que ansible no se ejecuta en Windows voy a usar WSL2 

![image](https://github.com/user-attachments/assets/9c504ee9-a1dd-407d-8778-4a925f2f4a98)

## ⚙️ Procedimiento

1. Actualizar los paquetes en Ubuntu.

![image](https://github.com/user-attachments/assets/f353bf98-d893-40fc-95bf-6e3a4c199702)


2. Instalar Ansible.

![image](https://github.com/user-attachments/assets/415dbf94-da40-4f3b-98ce-f11c989657cd)


3. Crear un directorio para el proyecto

![image](https://github.com/user-attachments/assets/cd746d58-b570-4b9d-89f0-8f90d39b34da)


4. Clonar el repositorio del proyecto.

![image](https://github.com/user-attachments/assets/b3108df2-e257-4cf6-9703-e8b2d9cc8e52)

5. Crear los roles para dividir la lógica del playbook.



6. Mover tareas, variables y plantillas a los roles correspondientes.
7. Actualizar el playbook principal (main.yml).
8. Validar la estructura y contenido de los archivos.
9. Ejecutar el playbook y comprobar el estado del servicio.






