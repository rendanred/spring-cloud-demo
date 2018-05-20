FROM index.alauda.cn/demo100/piggyjava 
MAINTAINER rendanred <rendanred@gmail.com>

ADD ./target/service-A-0.0.1-SNAPSHOT.jar  /app/
CMD ["java", "-Xmx200m", "-jar", "/app/service-A-0.0.1-SNAPSHOT.jar"]

EXPOSE 2222 7074
