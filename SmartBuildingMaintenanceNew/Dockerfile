FROM tomcat:9.0-jdk17-temurin
RUN sed -i 's/port="8080"/port="10000"/' /usr/local/tomcat/conf/server.xml
COPY dist/SmartBuildingMaintenanceNew.war /usr/local/tomcat/webapps/ROOT.war
EXPOSE 10000
