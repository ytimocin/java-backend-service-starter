# Start

1. docker-compose -f src/main/docker/infra-local.yaml up -d
2. mvn spring-boot:run -Dspring-boot.run.profiles=docker

# References

1. https://github.com/thombergs/code-examples/tree/master/spring-boot/data-migration/liquibase