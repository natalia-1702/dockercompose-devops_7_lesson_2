FROM ubuntu:18.04
RUN apt-get update
RUN apt-get install -y git
RUN apt-get install -y maven
WORKDIR /home/
RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git
WORKDIR /home/boxfuse-sample-java-war-hello/
RUN mvn package
WORKDIR /opt/
RUN cp /home/boxfuse-sample-java-war-hello/target/hello-1.0.war .
#CMD ["mvn", "package"]
