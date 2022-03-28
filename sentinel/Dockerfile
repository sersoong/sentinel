FROM openjdk:8u322-jdk-oracle
RUN mkdir -p /application
COPY sentinel-dashboard-1.8.3.jar /application/sentinel-dashboard.jar
WORKDIR /application
ENTRYPOINT ["java","-Dserver.port=8080","-Dcsp.sentinel.dashboard.server=0.0.0.0:8080","-Dsentinel.dashboard.auth.username=sentinel","-Dsentinel.dashboard.auth.password=123456","-jar","/application/sentinel-dashboard.jar"]
