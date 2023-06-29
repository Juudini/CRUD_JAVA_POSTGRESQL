# CRUD en Java con PostgreSQL, Docker y TablePlus

Este repositorio contiene un ejemplo de aplicación CRUD desarrollada en Java que utiliza una base de datos PostgreSQL para almacenar y manipular datos. La aplicación se ejecuta en un entorno Docker y se puede administrar utilizando TablePlus como cliente de base de datos.

## Requisitos previos

Asegúrate de tener instalados los siguientes componentes en tu sistema:

- Java Development Kit (JDK) 8 o superior
- Docker
- TablePlus (o cualquier otro cliente de base de datos que prefieras)

## Configuración de la base de datos

Antes de ejecutar la aplicación, debes configurar una base de datos PostgreSQL. Puedes hacerlo siguiendo estos pasos:

1. Abre una terminal y navega hasta el directorio raíz del proyecto.

2. Ejecuta el siguiente comando para iniciar un contenedor de Docker con PostgreSQL:

   ```bash
   docker-compose up -d

Esto iniciará un contenedor llamado java_db con una instancia de PostgreSQL en ejecución.

1.  Abre TablePlus (o tu cliente de base de datos preferido) y conecta con la base de datos utilizando los siguientes datos de conexión:

 ```bash
Host: localhost
Puerto: 5432
Nombre de usuario: postgres
Contraseña: postgres
Base de datos: postgres
```
Asegúrate de establecer una conexión exitosa con la base de datos antes de continuar.

- La aplicación ahora estará en ejecución y podrás realizar operaciones CRUD en la base de datos.