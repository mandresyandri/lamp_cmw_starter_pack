# Dockerfile
FROM php:8.2-apache

# Installez les extensions nécessaires, y compris le support PDO
RUN docker-php-ext-install pdo_mysql

# Copiez le contenu de votre application dans le répertoire web du conteneur
COPY ./html /var/www/html

# Exposez le port 80 du conteneur
EXPOSE 80
