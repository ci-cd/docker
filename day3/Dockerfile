FROM ubuntu:18.04
RUN echo "Hello World" > /hello_docker.txt
LABEL version="1.4" type="database" MAINTAINER="CDI Team" ubuntu="18.04" 
ENV JAVA_HOME="/some/directory"
ADD script.gz /
CMD ["/startup_script.sh"]
# ADD https://search.maven.org/remotecontent?filepath=log4j/log4j/1.2.17/log4j-1.2.17.tar.gz /root/log4j-1.2.17.tar.gz
ENTRYPOINT date