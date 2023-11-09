FROM openjdk:8

# Expose le port de votre application
EXPOSE 8022

# Copie le fichier JAR de votre application dans l'image
ADD target/devops_project.jar devops_project.jar

# Commande pour exécuter l'application
ENTRYPOINT ["java", "-jar", "/devops_project.jar"]

