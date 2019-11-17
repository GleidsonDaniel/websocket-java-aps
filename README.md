## Running

First, clone the project:

```bash
git clone git@github.com:GleidsonDaniel/websocket-java-aps.git
cd websocket-java-aps
```

Then run using Spring Boot Maven Plugin, specifying the exchange name (either ```liquid``` or ```bitmex```):

```bash
mvn spring-boot:run -Dspring-boot.run.profiles=$EXCHANGE_NAME
```

For example:

```bash
mvn spring-boot:run -Dspring-boot.run.profiles=bitmex
```



