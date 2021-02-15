FROM tomcat:9.0-alpine
RUN apk update && apk add git
RUN mkdir -p ./webapps/task
RUN git clone https://github.com/ArtemyevEvgeny/DocNew.git ./webapps/task
EXPOSE 8080
CMD ["catalina.sh", "run"]