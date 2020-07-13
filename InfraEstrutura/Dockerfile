FROM tomcat:8.0-jre8
COPY target/*.jar /app/application.jar
# Create app directory
WORKDIR /usr/local/tomcat/bin
CMD ["catalina.sh", "run"]
EXPOSE 8080 8081
ENTRYPOINT java -jar /app/application.jar
