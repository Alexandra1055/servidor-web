FROM php:8.2-apache

RUN apt-get update && apt-get install -y \
    libcurl4-openssl-dev unzip git \
 && docker-php-ext-install pdo_mysql curl \
 && a2enmod rewrite \
 && rm -rf /var/lib/apt/lists/*

#los comandos de Raul pero para docker
#(php -m | grep curl
#sudo phpdismod -v 8.3 curl
#sudo phpenmod -v 8.3 curl
#sudo apt install php-curl)
