FROM java:8
MAINTAINER breeze
ADD rocketmq-exporter-0.0.2-SNAPSHOT.jar quickstart.jar
EXPOSE 5557
ENTRYPOINT exec java $JAVA_OPTS -jar quickstart.jar
#ENTRYPOINT ["java","-jar","quickstart.jar"]
