# 1. Base image with Java runtime
FROM eclipse-temurin:21-jdk

# 2. Create working directory inside container
WORKDIR /app

# 3. Copy your .jar file from host to container
COPY target/*.jar app.jar
# 4. Run the jar file when container starts
ENTRYPOINT ["java", "-jar", "app.jar"]


