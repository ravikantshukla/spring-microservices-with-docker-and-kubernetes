FROM openjdk:8-jre-alpine
ENV APP_FILE organization-service-1.2-SNAPSHOT.jar
ENV APP_HOME /app
EXPOSE 0
COPY target/$APP_FILE $APP_HOME/
WORKDIR $APP_HOME
ENTRYPOINT ["sh", "-c"]
CMD ["exec java -jar $APP_FILE"]