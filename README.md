# data-notification-db-initializer

Database migartion for data-notification-subscription.

## :rocket: Running From Source

```
mvn clean install
```

```
mvn package
```

```
java -Djdbc.url=jdbc:postgresql://${db_host}:${db_port}/data_notification_subscription -Djdbc.username=${user_name} -Djdbc.password=${password} -jar target/data-notification-db-initializer-1.0-SNAPSHOT.jar
```
