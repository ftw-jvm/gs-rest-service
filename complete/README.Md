## Plain Spring native example 

Official Spring Native demo taken from:
https://docs.spring.io/spring-native/docs/current/reference/htmlsingle/

Setup tips (plugins and profile) taken from:
https://docs.spring.io/spring-native/docs/current/reference/htmlsingle/#_sample_project_setup

To run:
```
$ mvn package -DskipTests
$ java -jar target/rest-service-complete-0.0.1-SNAPSHOT.jar
$ mvn -P native package -DskipTests
$ target/rest-service-complete
```

Then, access the endpoint http://localhost:8080/greeting