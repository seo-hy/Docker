FROM ubuntu:14.04
LABEL email = "seok02h@khu.ac.kr"
LABEL name = "seohyun"
RUN apt-get update
RUN apt-get install -y nginx
RUN echo "this is a ubuntu container"
WORKDIR /etc/nginx
CMD ["nginx", "-g", "daemon off;"]
EXPOSE 80