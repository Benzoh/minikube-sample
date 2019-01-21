FROM php:7.2-apache
RUN apt-get update
RUN apt-get -y install vim wget mysql-client

ADD ./html/ /var/www/html/

RUN ls -lh /
