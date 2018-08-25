FROM index.alauda.cn/demo100/piggyjava 
MAINTAINER rendanred <rendanred@gmail.com>

ADD ./target/ribbon-0.0.1-SNAPSHOT.jar  /app/
CMD ["java", "-Xmx1024m", "-jar", "/app/ribbon-0.0.1-SNAPSHOT.jar"]

EXPOSE 7072
