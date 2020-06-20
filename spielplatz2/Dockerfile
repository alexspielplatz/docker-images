FROM centos:centos7
RUN groupadd -g 1999 appuser && useradd -r -u 1999 -g appuser appuser
RUN yum -y install epel-release
RUN yum -y update
RUN yum -y install htop
RUN yum -y install python3-pip
RUN pip3 install youtube-dl
USER appuser
CMD ["usr/bin/htop"]

