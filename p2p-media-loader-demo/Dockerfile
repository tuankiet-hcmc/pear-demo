FROM httpd:2.4

COPY . /usr/local/apache2/htdocs/

RUN apt-get update -y && apt-get install nodejs -y && npm install