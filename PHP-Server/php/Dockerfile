FROM php:7.3-apache
RUN apt-get update && apt-get upgrade -y
RUN docker-php-ext-install mysqli
EXPOSE 80
CMD ["/etc/apach2/"]
COPY  ./php/index1.php /var/www/html/

