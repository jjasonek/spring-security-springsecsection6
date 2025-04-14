# Udemy Course Spring Security Section6
## spring version: 3.4.4

## Docker container for MySQL
docker run -p 3306:3306 --name springsecurity -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=eazybank -d mysql


## Profiles

### Default behavior log message
No active profile set, falling back to 1 default profile: "default"
### Log message when prod profile is active (spring.profiles.active=prod)
The following 1 profile is active: "prod"

### using environment variable
in IntelliJ: SPRING_PROFILES_ACTIVE=default in Run Configuration -> "Environment variables"
in IntalliJ: prod in Run Configuration -> "Active profiles"
JVM parameter: java -jar -Dspring.profiles.active=prod eazybank-0.0.1-SNAPSHOT.jar
OS: export spring_profiles_active=dev (SPRING_PROFILES_ACTIVE=dev)
