
FROM debian:jessie

ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt-get install -y nginx
RUN echo 'Ciao corso docker' > /var/www/html/index.html

CMD nginx -g 'daemon off;'
EXPOSE 80
