FROM maven:3.6-jdk-8-alpine
COPY demo/pom.xml .
RUN mvn dependency:go-offline dependency:resolve-plugins dependency:resolve -B && \
    mvn dependency:get -Dartifact=org.apache.maven.surefire:surefire-junit-platform:2.22.2 && \
    rm -f pom.xml
