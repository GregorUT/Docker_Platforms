FROM centos:7
RUN yum install epel-release -y && yum update -y && yum install -y python-pip python-devel gcc gcc-devel libxml2 libxml2-devel libxslt libxslt-devel openssl openssl-devel libffi libffi-devel && pip install scrapy
RUN /bin/bash