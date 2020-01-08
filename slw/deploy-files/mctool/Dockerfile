FROM centos:latest

MAINTAINER slw

ENV TZ="/usr/share/zoneinfo/Asia/Shanghai"

WORKDIR /
ADD mctool /
EXPOSE 80

ENTRYPOINT exec tail -f /dev/null
