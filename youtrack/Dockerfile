FROM java:openjdk-7-jre
MAINTAINER Maarten Balliauw <maarten.balliauw@jetbrains.com>

RUN wget http://download-cf.jetbrains.com/charisma/youtrack-6.0.12577.jar -O youtrack.jar

EXPOSE 80
CMD ["java", "-Xmx1g", "-XX:MaxPermSize=250m", "-Djava.awt.headless=true", "-jar", "youtrack.jar", "80"]
