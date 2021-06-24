# Alpine Linux with OpenJDK JRE
FROM openjdk:8-jre-alpine

# Copy war file
COPY digiImmu-0.0.1-SNAPSHOT.jar /digiImmu-0.0.1-SNAPSHOT.jar
EXPOSE 8080
# run the app
CMD ["/usr/bin/java", "-jar", "/digiImmu-0.0.1-SNAPSHOT.jar"]

