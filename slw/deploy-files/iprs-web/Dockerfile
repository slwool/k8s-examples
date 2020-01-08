FROM openjdk:8u121

MAINTAINER slw

ENV TZ="/usr/share/zoneinfo/Asia/Shanghai"

WORKDIR /
ADD iprs-web-1.0.0.jar bootstrap.yml /
EXPOSE 80

ENTRYPOINT exec java $JAVA_OPTS -jar iprs-web-1.0.0.jar   --spring.cloud.bootstrap.location=/bootstrap.yml
