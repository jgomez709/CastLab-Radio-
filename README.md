Despliegue de CastLab con Docker

Este proyecto contiene la configuración necesaria para desplegar CastLab utilizando contenedores Docker.
⚠️ Importante:

Este repositorio no incluye el código fuente del sistema CastLab, sino solo los archivos docker-compose necesarios para construir las imágenes y publicar el sistema. Siéntase libre de usar esta configuración; solo debe descargar los archivos y colocarlos en la carpeta raíz de su sistema CastLab.
Requisitos de CastLab (Versión 3.0):

Esta configuración ha sido probada con la versión 3.0 de CastLab, que requiere los siguientes componentes:

    PHP 8.3
    MySQL 8.0+ o MariaDB 10.6+
    Extensiones PHP necesarias:
        BCMath
        Ctype
        cURL
        DOM
        Fileinfo
        GD
        JSON
        Mbstring
        OpenSSL
        PCRE
        PDO
        pdo_mysql
        Tokenizer
        XML
        Filter
        Hash
        Session
        Zip
    Funciones habilitadas:
        allow_url_fopen()
        file_get_contents()

Framework:

Este proyecto trabaja con Laravel 11. Todos los requisitos mencionados han sido tomados en cuenta para la generación de los archivos docker-compose.
Uso:

    Clone este repositorio en la carpeta raíz de su sistema CastLab.
    Ejecute los contenedores utilizando el archivo docker-compose.yml.

docker-compose up -d

Nota:

Siéntase libre de personalizar la configuración según sus necesidades. Esperamos que esta configuración le sea de gran ayuda para desplegar CastLab fácilmente.
