# Sample server eureka discovery

## Steps to Setup

**1. Clone the application**


**2. Define server port**
```bash
application.yml
```

**3. Build and run the app using maven**

```bash
mvn package
java -jar target/discovery-eureka-0.0.1-SNAPSHOT.jar

```

Alternatively, you can run the app without packaging it using -

```bash
mvn spring-boot:run
```

The app will start running at <http://localhost:9090>.
