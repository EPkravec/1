
FROM openjdk:8-jdk-alpine as java
RUN sudo apt update && apt install -y maven
COPY ./ ./
WORKDIR /crud_pg_mvp
RUN mvn clean package
ENTRYPOINT ["java", "-jar", "target/crud_mvp_demo.1.0.jar"]


#FROM ubuntu:18.04
#MAINTAINER kep
##COPY --from=java ./ ./crud_pg_mvp
#COPY --from=java /home/$USER/src /home/$USER/src
#CMD ["echo", "started"]