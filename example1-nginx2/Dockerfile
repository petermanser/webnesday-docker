FROM ubuntu:14.04

RUN apt-get update && apt-get install -y nginx

RUN echo 'Webnesday Example 1' > /usr/share/nginx/html/index.html

CMD nginx -g "daemon off;"

EXPOSE 80
