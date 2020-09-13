# spring-config-client

This app is reading configs from the config server: https://github.com/rakeshkr114/spring-config-server ::
https://github.com/rakeshkr114/spring-config-server/blob/master/config-client.properties

Use POST:  http://localhost:8981/actuator/refresh
to force clients to refresh configs from server (if configs got updated)


specify config server details in : bootstrap.properties -
https://github.com/rakeshkr114/spring-config-client/blob/master/src/main/resources/bootstrap.properties

