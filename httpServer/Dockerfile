FROM httpd:2.4.53-alpine3.15

COPY ./www/ /usr/local/apache2/htdocs/
COPY ./apache.conf /usr/local/apache2/conf/httpd.conf

RUN apk update \
		apk add php8 php8-apache2 php8-common php8-cgi php8-gd php8-zip php8-mysqlnd php8-mysqli php8-mbstring php8-curl
