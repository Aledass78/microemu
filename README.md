## Build

- Download Maven 3.0.5
- OpenJDK 8

Run in terminal:

```bash
mvn clean install -DskipTests -Dgpg.skip -Dproguard.skip=true
