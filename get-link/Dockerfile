FROM php:7.2-apache
COPY src/ /var/www/html

RUN a2enmod headers && service apache2 restart
EXPOSE 80

#WORKDIR /root/docker-php
#CMD [ "php", "/root/docker-php/src/index.php" ]
