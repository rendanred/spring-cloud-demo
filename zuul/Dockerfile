FROM index.alauda.cn/demo100/piggyjava 
MAINTAINER rendanred <rendanred@gmail.com>

ADD ./target/zuul-0.0.1-SNAPSHOT.jar  /app/
CMD ["java", "-Xmx1024m -Xms1024m -Xmn512m", "-jar", "/app/zuul-0.0.1-SNAPSHOT.jar"]

EXPOSE 7073
