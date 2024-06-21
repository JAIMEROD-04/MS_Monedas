# Usa una imagen base de Java 17
FROM openjdk:17-jdk-slim

# Establece el directorio de trabajo dentro del contenedor
WORKDIR /app

# Copia el archivo JAR de tu aplicación al directorio de trabajo del contenedor
COPY target/MS_Moneda-0.0.1-SNAPSHOT.jar app.jar

# Exponer el puerto en el que tu aplicación estará escuchando
EXPOSE 8020

# Comando para ejecutar la aplicación
ENTRYPOINT ["java", "-jar", "app.jar"]

