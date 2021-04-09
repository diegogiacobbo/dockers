FROM node:latest
MAINTAINER Diego Giacobo
COPY . /var/www
WORKDIR /var/www
RUN npm install
ENTRYPOINT ["npm", "start"]
EXPOSE 3000