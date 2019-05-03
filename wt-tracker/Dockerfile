FROM node:10.14.2

WORKDIR /usr/app

COPY . .
RUN apt-get install git && npm install --quiet && npm run build