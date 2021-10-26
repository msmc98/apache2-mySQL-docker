
# PHP + Apache
FROM php:7.4-apache

#creacion de repositorio
WORKDIR /var/www/html

#comandos para instalar git y descargar el repositorio
RUN apt-get upgrade
RUN apt-get update
RUN apt-get -y install git
RUN git clone https://github.com/drnic/php-helloworld.git

#mover arvhico para poder verlo
RUN mv php-helloworld/index.php /var/www/html