FROM centos:latest
LABEL maintainer="fox" description="Install tree vim*"
RUN rpm -qa | grep tree || yum install -y tree \
	vim*

