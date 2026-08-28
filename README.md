# hello-world-maven

Hello World Java program built with Maven (maven-archetype-quickstart) for CIS-055 Data Structures.

## Run

```
mvn compile org.codehaus.mojo:exec-maven-plugin:3.5.0:java -Dexec.mainClass=com.joelperez.hello.App
```

Or open the folder in VS Code and press Run on `src/main/java/com/joelperez/hello/App.java`.

## Test

```
mvn test
```

## Requirements

- JDK 25 (JAVA_HOME set)
- Apache Maven 3.9+
