#FROM ubuntu:18.04
FROM tomcat:10.0-jdk11-openjdk

#RUN apt-get update
#RUN apt-get install -y curl
#RUN apt-get install -y default-jdk
#WORKDIR /opt/tomcat
#RUN curl -O https://apache-mirror.rbc.ru/pub/apache/tomcat/tomcat-8/v8.5.56/bin/apache-tomcat-8.5.56.tar.gz
#RUN tar xvfz apache-tomcat-8.5.56.tar.gz
#RUN mv apache-tomcat-8.5.56/* /opt/tomcat/.

#RUN ls -la /home/boxfuse-sample-java-war-hello/
#RUN cp /opt/hello-1.0.war /usr/local/tomcat/webapps/
EXPOSE 8080
#CMD ["cp", "/home/boxfuse-sample-java-war-hello/target/hello-1.0.war", "/opt/tomcat/webapps/"]
CMD ["catalina.sh", "run"]
