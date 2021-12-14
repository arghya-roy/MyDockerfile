FROM ubuntu
MAINTAINER suvo
WORKDIR /newworkdir
RUN apt-get update -y
ENV mynane arghya
COPY dir1/file1 /copy/              #docker uses relative directory, If I gave /ec2-user/dir1/file1 then it was failed.
ADD https://www.win-rar.com/predownload.html?&L=0 /copy2     #copy2 is a file