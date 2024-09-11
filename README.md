# Despliegue de CastLab con Docker

Este proyecto contiene la configuración necesaria para desplegar **CastLab** utilizando contenedores Docker.

## ⚠️ Importante:
Este repositorio **no** incluye el código fuente del sistema **CastLab**, sino únicamente los archivos `docker-compose` necesarios para construir las imágenes y desplegar el sistema. Siéntase libre de usar esta configuración; solo debe descargar los archivos y colocarlos en la carpeta raíz de su instalación de **CastLab**.

## Requisitos de CastLab (Versión 3.0):

Esta configuración ha sido probada con la versión **3.0** de **CastLab**, la cual tiene los siguientes requisitos:

- **PHP** 8.3
- **MySQL** 8.0+ o **MariaDB** 10.6+
- Extensiones PHP requeridas:
  - BCMath
  - Ctype
  - cURL
  - DOM
  - Fileinfo
  - GD
  - JSON
  - Mbstring
  - OpenSSL
  - PCRE
  - PDO
  - pdo_mysql
  - Tokenizer
  - XML
  - Filter
  - Hash
  - Session
  - Zip
- Funciones habilitadas:
  - `allow_url_fopen()`
  - `file_get_contents()`

## Framework:
Esta versión trabaja con **Laravel 11**. Todos estos requisitos han sido tomados en cuenta para la generación de los archivos `docker-compose`.

## Uso:
1. Clona este repositorio en la carpeta raíz de tu sistema **CastLab**.
2. Ejecuta los contenedores utilizando el archivo `docker-compose.yml` con el siguiente comando:

   ```bash
   docker-compose up -d
