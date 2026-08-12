# CI/CD Tomcat Web Application

GitHub → Jenkins → Maven → WAR → Apache Tomcat → Browser

## Build
mvn clean package

WAR output:
target/ci-cd-tomcat-webapp.war

## Application URL
http://YOUR-EC2-PUBLIC-IP:8080/ci-cd-tomcat-webapp/
