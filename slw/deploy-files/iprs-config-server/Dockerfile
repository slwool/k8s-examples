FROM openjdk:8u121

MAINTAINER slw

ENV TZ="/usr/share/zoneinfo/Asia/Shanghai"

WORKDIR /
ADD iprs-config-server-1.0.3.jar bootstrap.yml /
EXPOSE 80

ENTRYPOINT exec java $JAVA_OPTS -jar iprs-config-server-1.0.3.jar --spring.cloud.bootstrap.location=/bootstrap.yml 
