FROM ubuntu:20.04

LABEL version="0.0.0"
LABEL description="Sakata-shoten Developing Environment"

ENV DEBIAN_FRONTEND=noninteractive

RUN mkdir -p /var/Sakata-shoten
RUN apt update
RUN apt install -y wget && apt install -y vim && apt install -y git && apt install -y nodejs npm
RUN npm install express --save &&  npm install react --save && npm install mysql --save
