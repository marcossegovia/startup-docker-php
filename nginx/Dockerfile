FROM nginx:latest
MAINTAINER Marcos Segovia <velozmarkdrea@gmail.com>

ARG TIMEZONE

RUN ln -snf /usr/share/zoneinfo/${TIMEZONE} /etc/localtime && echo ${TIMEZONE} > /etc/timezone

COPY conf /etc/nginx

EXPOSE 80
EXPOSE 443
