#Servicio de Apache2 con Ubuntu
FROM ubuntu:latest
MAINTAINER Víctor Laínez "vlainezt07@gmail.com"
ENV DEBIAN_FRONTEND noninteractive
RUN apt-get update
RUN apt-get -y install apache2
expose 80
CMD /usr/sbin/apache2ctl -D FOREGROUND
