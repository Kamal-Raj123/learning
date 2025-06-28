FROM ubuntu:v.01
WORKDIR /app
RUN apt-get update && apt-get install -y nginx
COPY ./html /var/www/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
#
