# Slightly modified version of MicroEmu that allows changing the platform name



## Build

- Download Maven 3.0.5
- OpenJDK 8

Run in terminal:

```bash
mvn clean install -DskipTests -Dgpg.skip -Dproguard.skip=true
```
---

  After the build, the JAR will be located at: `microemulator/target/microemulator-2.0.4.jar`

## You can run the emulator with a custom platform name using:
```bash
java -Dme.platform="Your very original platform" -jar microemulator-2.0.4.jar
```
