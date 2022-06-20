FROM registry.access.redhat.com/redhat-openjdk-18/openjdk18-openshift:1.12-1.1655301789

EXPOSE 8080

COPY app/passwordapi.jar /app/passwordapi.jar

CMD [ "java","-jar","/app/passwordapi.jar" ]