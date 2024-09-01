FROM ubuntu:latest
FROM nginx:latest

RUN apt-get update && apt-get upgrade -y

COPY softy-pinko-front-end /var/www/html/softy-pinko-front-end
COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf

EXPOSE 9000

CMD ["nginx", "-g", "daemon off;"]