FROM jenkins
MAINTAINER subhashvasarapu <aryansubhash999@gmail.com>

COPY plugins.txt /usr/share/jenkins/plugins.txt
RUN /usr/local/bin/plugins.sh /usr/share/jenkins/plugins.txt
