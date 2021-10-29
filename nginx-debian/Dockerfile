#Servicio nginx con Debian
FROM debian:latest
MAINTAINER Douglas Hernandez "douglasalexander683@gmail.com"
ENV DEBIAN_FRONTEND noninteractive
RUN apt-get update
RUN apt-get -y install nginx
expose 80
CMD nginx -g "daemon off;"
