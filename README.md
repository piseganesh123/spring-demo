# Spring Boot Web Application
This repository has the project files for a tutorial series on Spring Boot available from by website at [Spring Framework Guru](https://springframework.guru)

## Checkout the full tutorial here!
[Spring Boot - making Spring Fun again!](https://springframework.guru/spring-boot-web-application-part-1-spring-initializr/)

Commit code triggers github action, commits container in dhub, helm chart in ECR.
replace docker image tag with appropriate helm chart version and install application using below helm command 

helm upgrade --install spring-demo ./spring-demo-app/ --version <2024.3.12-103624>
