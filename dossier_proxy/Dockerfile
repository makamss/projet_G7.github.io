FROM ubuntu/apache2
        
LABEL Role=proxy-entrant

RUN a2enmod proxy proxy_http

COPY apache2.conf /etc/apache2/apache2.conf
        
EXPOSE 80
