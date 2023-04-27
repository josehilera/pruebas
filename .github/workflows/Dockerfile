FROM tomcat:8.0-alpine
ADD target/Baloncesto.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD bin/catalina.sh start && /bin/sh