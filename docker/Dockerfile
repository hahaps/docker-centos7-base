FROM centos:7.2.1511

COPY Centos-7.repo /Centos-7.repo

LABEL name="CentOS7 Base Image with git" \
    vendor="" \
    license="MIT" \
    build-date="20170912"

MAINTAINER Li Xipeng <lixipeng@prophetech.cn>

# Use centos7 repo of ali
# RUN rm -rf /etc/yum.repos.d/* \
#     && mv /Centos-7.repo /etc/yum.repos.d/ \
#     && yum clean all && yum makecache

# Install git
RUN yum install -y git

CMD ["/bin/bash"]
