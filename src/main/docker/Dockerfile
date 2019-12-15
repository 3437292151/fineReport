from tomcat:jdk8-openjdk
MAINTAINER 18708339626@163.com #作者
RUN rm -rf /usr/local/tomcat/webapps/*
COPY finereport-0.0.1-SNAPSHOT.war /usr/local/tomcat/webapps #放置到tomcat的webapps目录下
ENV TZ=Asia/Shanghai
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone