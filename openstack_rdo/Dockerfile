FROM fedora:

RUN yum update -y
RUN yum install -y https://rdoproject.org/repos/rdo-release.rpm
RUN yum install -y openstack-packstack
RUN packstack --allinone
