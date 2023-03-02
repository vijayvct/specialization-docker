FROM ubuntu

LABEL "maintainer"="Vijay Vishwakarma"
LABEL "version"="1.0.1"

RUN apt-get update

RUN apt install apache2 -y
RUN apt install apache2-utils -y

EXPOSE 80 
CMD ["apache2ctl", "-D", "FOREGROUND"]