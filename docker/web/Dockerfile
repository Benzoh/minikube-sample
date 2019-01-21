FROM php:7.2-apache
RUN apt-get update
RUN apt-get -y install vim wget mysql-client curl \
  && docker-php-ext-install pdo_mysql \
  && apt-get clean \
  && rm -rf /var/cache/apt/archives

ADD html/ /var/www/html/
COPY script/ /tmp/

# RUN ls -lh /
