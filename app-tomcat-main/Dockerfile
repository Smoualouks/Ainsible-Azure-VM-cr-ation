FROM tomcat:latest

LABEL maintainer="Group4"

ADD ./target/LoginWebApp-1.war /usr/local/tomcat/webapps/
ADD ./index.html /usr/local/tomcat/webapps/test/index.html
EXPOSE 8082

CMD ["catalina.sh", "run"]
