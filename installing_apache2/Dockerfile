FROM ubuntu
MAINTAINER Arghya
ENV DEBIAN_FRONTEND noninteractive
RUN apt-get update && apt-get install -y apache2 && apt-get clean && rm -rf /var/lib/apt/list/*
ENV APACHE_RUN_USER www-data
ENV APACHE_RUN_GROUP www-data
ENV APACHE_LOG_DIR /var/log/apache2
EXPOSE 80
CMD [ "/usr/sbin/apache2", "-D", "FOREGROUND" ]

