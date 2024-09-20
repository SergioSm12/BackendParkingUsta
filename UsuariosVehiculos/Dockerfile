FROM openjdk:17-jdk-slim
ARG JAR_FILE=target/UsuariosVehiculos-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} usuarios_vehiculos.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "usuarios_vehiculos.jar"]