FROM ubuntu:24.04

RUN apt update -y && apt install -y apache2 && \
  echo "Hello world from Docker!" > /var/www/html/index.html

CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]

EXPOSE 80
