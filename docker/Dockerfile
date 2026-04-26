FROM openjdk:8-jdk-alpine 

EXPOSE 8070

ENV APP_HOME /usr/src/app

ENV DOCKER_API_VERSION=1.44

COPY target/shopping-cart-0.0.1-SNAPSHOT.jar $APP_HOME/app.jar

WORKDIR $APP_HOME

ENTRYPOINT ["java", "-jar", "app.jar"]
