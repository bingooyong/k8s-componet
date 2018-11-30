FROM       centos:centos7
MAINTAINER lvyong1985 <lvyong1985@gmail.com>

# 设置环境变量
ENV TZ Asia/Shanghai

ADD aliyun-mirror.repo /etc/yum.repos.d/CentOS-Base.repo
ADD aliyun-epel.repo /etc/yum.repos.d/epel.repo

RUN yum install -y curl wget tar unzip && yum clean all

WORKDIR /home

