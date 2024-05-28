FROM openjdk:17

WORKDIR /app

COPY target/recipes-0.0.1-SNAPSHOT.war /app/app.war

EXPOSE 7071

CMD ["java", "-jar", "app.war"]
