FROM fedora:latest

RUN yum -y install 2048-cli && \
    yum clean all && \
    rm -rf /var/cache/yum

CMD 2048 -c
