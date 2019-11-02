FROM centos-ssh

# install java 1.8 and set env
ADD jdk-8u221-linux-x64.tar.gz /usr/local/
RUN mv /usr/local/jdk1.8.0_221 /usr/local/jdk1.8
ENV JAVA_HOME /usr/local/jdk1.8
ENV PATH $JAVA_HOME/bin:$PATH

# install hadoop and set env
ADD hadoop-2.7.7.tar.gz /usr/local/
RUN mv /usr/local/hadoop-2.7.7 /usr/local/hadoop
ENV HADOOP_HOME /usr/local/hadoop
ENV PATH $HADOOP_HOME/bin:$PATH

#install which
RUN yum install -y which