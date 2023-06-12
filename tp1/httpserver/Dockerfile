# Our base image
FROM httpd:2.4

# le contenu des page html
COPY ./public-html/ /usr/local/apache2/htdocs/

# le contenu de la configuration
COPY ./my-httpd.conf /usr/local/apache2/conf/httpd.conf