FROM nginx:latest

WORKDIR /var/socket

RUN usermod -u 1000 nginx && groupmod -g 1000 nginx && chown -R nginx:nginx /var/socket