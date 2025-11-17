# Sistema Integral de Gestión para Microempresas de Abarrotes

## Proyecto Terminal – Ingeniería en Teleínformatica

* Desarrollado por: César Adrián Gabriel Cruz
* Materia: Seminario de Proyecto Terminal
* Profesor: Jorge Luis Dávila Guerrero

### 1. Descripción General del Proyecto

El Sistema Integral de Gestión para Microempresas de Abarrotes es una solución tecnológica diseñada para optimizar los procesos internos de pequeños comercios, especialmente tiendas de abarrotes que requieren herramientas sencillas, eficientes y accesibles para administrar sus operaciones diarias.

El sistema permite gestionar:
* Cortes de caja
* Inventarios
* Control de empleados (con roles basados en permisos)
* Ventas y movimientos
* Reportes básicos
* Acceso seguro mediante diferentes perfiles de usuario
* Este proyecto representa la Versión 1, correspondiente a la entrega final del proyecto terminal universitario. Su código no se mantiene activo actualmente, pero se conserva con fines de consulta, documentación y portafolio académico.

### 2. Objetivo

Desarrollar un sistema funcional que permita a microempresarios tener un mejor control sobre sus procesos administrativos, reduciendo errores humanos y mejorando la eficiencia de atención y operación.

### 3. Tecnologías Utilizadas
    3.1 Lenguajes y Backend
        * PHP 8.2.12
        * MySQL / MariaDB
        * HTML5
        * CSS3
        * JavaScript
    3.2 Entorno de Desarrollo
        * Servidor local XAMPP
        * phpMyAdmin
        * Navegadores (Chrome, Brave, Edge, Firefox)

### 4. Requisitos del Sistema

    4.1 Requisitos de Software
        * Windows 10 / 11, macOS o Linux
        * XAMPP (recomendado)
        * PHP 8.2+
        * MariaDB o MySQL
        * Navegador actualizado

    4.2 Base de Datos

Se incluye una base de datos de ejemplo en la carpeta /documents/Proyecto_Sistema Integral de Gestión para Microempresas de Abarrotes_BD.sql, diseñada exclusivamente para propósitos académicos y pruebas locales.

### 5. Instalación / Cómo Ejecutar el Proyecto

    5.1 Instalar XAMPP

Descargar desde: https://www.apachefriends.org/

    5.2 Copiar el proyecto

Colocar la carpeta principal dentro de:

C:\xampp\htdocs\

    5.3 Crear la base de datos

Abrir phpMyAdmin

Crear una base de datos con el nombre:

b8_38213116_santana

Importar el archivo SQL ubicado en:
/documents/Proyecto_Sistema Integral de Gestión para Microempresas de Abarrotes_BD.sql

    5.4 Verificar la conexión

Revisar el archivo:

includes/conexion_db.php

Parámetros sugeridos (solo para entorno local):

private $host = "localhost";
private $db_name = "b8_38213116_santana";
private $username = "root";
private $password = "";

    5.5 Ejecutar

Abrir el navegador:

http://localhost/CorteCaja/

### 6. Roles y Usuarios de Prueba

El sistema cuenta con diferentes niveles de privilegios:

* Rol	Usuario	Contraseña
* Gerente	Pipis	Pipis
* Encargado	Cesar	Cesar
* Cajero	Ramon	Ramon

(Estos usuarios corresponden al contenido de prueba dentro de la base de datos ejemplo.)

### 7. Funcionalidades Principales

* Inicio de sesión con tres niveles de rol
* Panel de control según permisos
* Registro de ventas
* Consulta de históricos
* Generación de cortes de caja
* Gestión de inventario
* Control básico de empleados
* Interfaz orientada a operación rápida

### 8. Documentación

Todo el material relacionado con la investigación, diseño, análisis y desarrollo se encuentra en la carpeta:

/documents/

Incluye:

* Presentación del proyecto
* Casos de uso
* Diagramas
* Tecnologías utilizadas
* Manual de usuario
* Manual técnico
* Reporte final académico

### 9. Estado del Proyecto

* Versión: 1.0
* Estado: Finalizado (no recibe mantenimiento)
* Uso: Académico / Portafolio
* Propietario: César Adrián Gabriel Cruz

Este repositorio preserva la versión entregada en la universidad y sirve como referencia histórica y profesional.

### 10. Créditos

Desarrollado por:

* César Adrián Gabriel Cruz
* Egresado de Ingenieria en Teleínformatica
* Proyecto Terminal – Evaluación Final