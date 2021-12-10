FROM ubuntu
MAINTAINER arghya
RUN apt-get update
RUN apt-get install -y nginx
# we have to create a index.html file in host first
ADD index.html /usr/share/nginx/html/index.html
ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]
EXPOSE 80