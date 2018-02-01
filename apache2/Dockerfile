FROM ubuntu

MAINTAINER amanoese<amanoese@gmail.co.>

RUN apt-get update && apt-get install -y apache2
RUN echo ServerName localhost > /etc/apache2/conf-available/fqdn.conf
RUN a2enconf fqdn

CMD apache2ctl start && bash
