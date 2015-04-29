FROM debian:wheezy
MAINTAINER Gao Chongzhe <kousuutetu@163.com>
RUN apt-get update \
    && apt-get upgrade -y \
    && apt-get install -y openssh-server vim wget
COPY    entry /bin/entry
EXPOSE  22
ENTRYPOINT /bin/entry && /bin/bash
