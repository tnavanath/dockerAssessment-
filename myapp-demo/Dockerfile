
FROM openjdk:8-jdk

MAINTAINER navanath.temgire@morningstar.com

EXPOSE  8080
WORKDIR "/usr/local/openjdk/"

# RUN ["rm","-R","webapps/ROOT"]

ADD *.jar /usr/local/openjdk/webapps/ROOT.jar

CMD ["catalina.sh","run"]