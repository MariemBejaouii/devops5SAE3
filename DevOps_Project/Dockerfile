FROM openjdk:8

EXPOSE 8022

# Copie le fichier JAR de votre application dans l'image
ADD target/devops_project.jar devops_project.jar

ENTRYPOINT ["java", "-jar", "/devops_project.jar"]


