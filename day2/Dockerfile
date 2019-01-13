FROM ubuntu:18.04
RUN echo "Hello World" > /hello_docker.txt
LABEL version="1.4" type="database" MAINTAINER="CDI Team" ubuntu="18.04" 
ENV JAVA_HOME="/some/directory"
ADD script.gz /
CMD ["/startup_script.sh"]
