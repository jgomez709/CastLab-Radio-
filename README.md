# CastLab Deployment with Docker

This project contains the necessary configuration to deploy **CastLab** using Docker containers.

## ⚠️ Important:
This repository **does not** include the source code of the **CastLab** system, but only the necessary `docker-compose` files to build the images and deploy the system. Feel free to use this configuration; you just need to download the files and place them in the root directory of your **CastLab** system.

## CastLab Requirements (Version 3.0):

This setup has been tested with **CastLab** version **3.0**, which has the following requirements:

- **PHP** 8.3
- **MySQL** 8.0+ or **MariaDB** 10.6+
- Required PHP extensions:
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
- Enabled functions:
  - `allow_url_fopen()`
  - `file_get_contents()`

## Framework:
This version works with **Laravel 11**. All these requirements have been considered for the generation of the `docker-compose` files.

## Usage:
1. Clone this repository into the root directory of your **CastLab** system.
2. Run the containers using the `docker-compose.yml` file with the following command:

   ```bash
   # CastLab Deployment with Docker

This project contains the necessary configuration to deploy **CastLab** using Docker containers.

## ⚠️ Important:
This repository **does not** include the source code of the **CastLab** system, but only the necessary `docker-compose` files to build the images and deploy the system. Feel free to use this configuration; you just need to download the files and place them in the root directory of your **CastLab** system.

## CastLab Requirements (Version 3.0):

This setup has been tested with **CastLab** version **3.0**, which has the following requirements:

- **PHP** 8.3
- **MySQL** 8.0+ or **MariaDB** 10.6+
- Required PHP extensions:
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
- Enabled functions:
  - `allow_url_fopen()`
  - `file_get_contents()`

## Framework:
This version works with **Laravel 11**. All these requirements have been considered for the generation of the `docker-compose` files.

## Usage:
1. Clone this repository into the root directory of your **CastLab** system.
2. Run the containers using the `docker-compose.yml` file with the following command:

   ```bash
   docker-compose up --build
