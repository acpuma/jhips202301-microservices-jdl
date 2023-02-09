## Java Microservices with Spring Cloud Config and JHipster

https://developer.okta.com/blog/2019/05/23/java-microservices-spring-cloud-config

https://www.youtube.com/watch?v=ez7HMO60kE8

```
jhipster import-jdl apps.jh

mvn -Pprod verify com.google.cloud.tools:jib-maven-plugin:dockerBuild

cd docker-compose
docker-compose up -d
```

/etc/hosts

127.0.0.1  keycloak
