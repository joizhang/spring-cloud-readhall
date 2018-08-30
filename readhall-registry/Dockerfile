FROM java:9-jre
MAINTAINER Alexander Lukyanchikov <sqshq@sqshq.com>

ADD ./target/registry.jar /app/
CMD ["java", "-Xms200m", "-Xmx200m", "-XX:+HeapDumpOnOutOfMemoryError", "-jar", "/app/registry.jar"]

EXPOSE 8761