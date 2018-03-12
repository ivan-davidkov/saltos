FROM centos:7.4.1708

RUN yum update -y 
RUN yum -y install epel-release
RUN yum -y install salt-master

EXPOSE 4505 4506

# ENTRYPOINT ["/usr/bin/salt-master"]
