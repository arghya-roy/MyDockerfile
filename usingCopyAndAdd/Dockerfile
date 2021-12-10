# at first we have to create testfile.txt and test.tar.gz in host machine
FROM ubuntu
WORKDIR /tmp
RUN echo "arghya roy" > tmp/file1
ENV myname arghya
COPY testfile.txt /tmp/
ADD test.tar.gz /tmp/