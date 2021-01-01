FROM teamnerds/maven-spring-boot:mvn-3.6-jdk-8-spring-boot-2.3.7-alpine
RUN mvn dependency:get -Dartifact=org.springframework.cloud:spring-cloud-starter-netflix-zuul:2.2.6.RELEASE && \
    mvn dependency:get -Dartifact=org.springframework.cloud:spring-cloud-starter-netflix-eureka-server:2.2.6.RELEASE && \
    mvn dependency:get -Dartifact=org.springframework.cloud:spring-cloud-starter-netflix-eureka-client:2.2.6.RELEASE && \
    mvn dependency:get -Dartifact=org.springframework.boot:spring-boot-starter-actuator:2.3.7.RELEASE && \
    mvn dependency:get -Dartifact=org.springframework.boot:spring-boot-starter-data-jpa:2.3.7.RELEASE && \
    mvn dependency:get -Dartifact=org.springframework.boot:spring-boot-starter-test:2.3.7.RELEASE && \
    mvn dependency:get -Dartifact=io.springfox:springfox-swagger2:2.9.2 && \
    mvn dependency:get -Dartifact=io.springfox:springfox-swagger-ui:2.9.2 && \
    mvn dependency:get -Dartifact=com.google.code.findbugs:jsr305:3.0.2 && \
    mvn dependency:get -Dartifact=org.projectlombok:lombok:1.18.16 && \
    mvn dependency:get -Dartifact=io.swagger.core.v3:swagger-annotations:2.1.6 && \
    mvn dependency:get -Dartifact=io.swagger.codegen.v3:swagger-codegen-maven-plugin:3.0.23 && \
    mvn dependency:get -Dartifact=mysql:mysql-connector-java:8.0.22
