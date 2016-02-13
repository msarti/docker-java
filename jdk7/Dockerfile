FROM centos:7
MAINTAINER Marco Sarti <marco.sarti@gmail.com>
ENV container docker
ENV JAVA_HOME=/usr/lib/jvm/java-1.7.0-openjdk

RUN curl -L http://repos.fedorapeople.org/repos/dchen/apache-maven/epel-apache-maven.repo -o /etc/yum.repos.d/epel-apache-maven.repo

RUN yum -y update

RUN yum -y install java-1.7.0-openjdk-devel 


