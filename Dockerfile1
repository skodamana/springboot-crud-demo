FROM java
MAINTAINER shaileshkodamana
RUN mkdir -p /opt/apps/product
COPY target/spring-boot-web-0.0.2-SNAPSHOT.jar /opt/apps/product
ENTRYPOINT ["java","-jar","/opt/apps/product/spring-boot-web-0.0.2-SNAPSHOT.jar"]
