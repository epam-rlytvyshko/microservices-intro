# Smaller OS footprint using JRE
FROM eclipse-temurin:21-jre
WORKDIR /app

# Copy only the Jar from the current dir
# ADD build/libs/*.jar /app/app.jar
COPY build/libs/resources-service-1.0-SNAPSHOT.jar app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]
#CMD ["java", "-jar", "app.jar"]

