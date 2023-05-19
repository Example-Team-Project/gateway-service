# Gateway for learning project

The project requires an API Gateway and Spring has a nice and simple Gateway project.

This service is built on [Spring Cloud Gateway](https://cloud.spring.io/spring-cloud-gateway/reference/html/), and configured to forward requests to the DVD rental service. Eg: film-, actor- and inventory services (at the time of writing).

## Base configuration

Every configuration is placed into [application.yml](./src/main/resources/application.yaml).

## Future plan

When the service is deployed into a docker env or to k8s it would be nice to get the configuration somewhere else.

eg: external file mounted into container, mounted ConfigMap into a file.

