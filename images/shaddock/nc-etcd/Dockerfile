FROM shaddock/nc-scratch:latest
MAINTAINER epheo

RUN curl -L https://github.com/coreos/etcd/releases/download/v2.2.3/etcd-v2.2.3-linux-amd64.tar.gz -o etcd-v2.2.3-linux-amd64.tar.gz; \
    tar xzvf etcd-v2.2.3-linux-amd64.tar.gz; \
    cd etcd-v2.2.3-linux-amd64;

EXPOSE 4001 7001 2379 2380
CMD [ "/etcd-v2.2.3-linux-amd64/etcd" ]
