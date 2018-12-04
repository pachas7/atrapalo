FROM alpine:latest

RUN apk add apache2 php5-apache2

COPY index.php /var/www/localhost/htdocs/index.php
COPY docker-entrypoint.sh /

ENTRYPOINT ["sh" , "/docker-entrypoint.sh"]
