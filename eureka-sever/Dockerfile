FROM index.alauda.cn/demo100/piggyjava 
MAINTAINER rendanred <rendanred@gmail.com>

ADD ./target/eureka-sever-0.0.1-SNAPSHOT.jar  /app/
CMD ["java", "-Xmx1024m", "-jar", "/app/eureka-sever-0.0.1-SNAPSHOT.jar"]

EXPOSE 7071
