FROM ubuntu:18.04


RUN apt-get update && apt-get install -y openjdk-8-jdk

ENV JAVA_HOME /usr/lib/jvm/java-8-openjdk-amd64
ENV PATH /usr/java/bin:/usr/local/apache-maven/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin

COPY ./HelloExample.java /src/java/HelloExample.java

ENTRYPOINT ["tail", "-f", "/dev/null"]



