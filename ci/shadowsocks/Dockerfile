FROM ubuntu:16.04

RUN apt-get update && apt-get install -y \
    python-pip \
 && pip install git+https://github.com/shadowsocks/shadowsocks.git@master

COPY shadowsocks.json /etc

ENTRYPOINT ["ssserver", "-c", "/etc/shadowsocks.json"]
