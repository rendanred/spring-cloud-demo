FROM index.alauda.cn/demo100/piggyjava 
MAINTAINER Alexander Lukyanchikov <sqshq@sqshq.com>

ADD ./target/classes/service-A.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/service-A.jar"]

EXPOSE 2222 7074
