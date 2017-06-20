FROM tomcat:8-jre8  
MAINTAINER adenovariyanto@itgroupinc.asia 

RUN echo "export JAVA_OPTS=\"-Dapp.env=staging\"" > /usr/local/tomcat/bin/setenv.sh  

COPY ./app/application.war /usr/local/tomcat/webapps/staging.war

CMD ["catalina.sh", "run"]  
