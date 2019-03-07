FROM amazonlinux:latest
RUN yum install httpd php -y

EXPOSE 80

ADD app/ /var/www/html/

CMD apachectl -D FOREGROUND

