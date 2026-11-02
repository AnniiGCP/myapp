# Java Maven Laboratory Application

[![Java](https://img.shields.io/badge/Java-11%2B-ED8B00.svg?logo=openjdk&logoColor=white)](.)
[![Maven](https://img.shields.io/badge/Maven-Build-C71A36.svg?logo=apachemaven&logoColor=white)](.)
[![JUnit](https://img.shields.io/badge/JUnit-4.13-25A162.svg)](.)

A standard Apache Maven archetype Java application and automated test harness developed for university software engineering and DevOps laboratory coursework.

---

## Project Structure

```
myapp/
├── pom.xml                 # Project Object Model (dependencies & plugins)
├── src/
│   ├── main/java/          # Application source code
│   └── test/java/          # JUnit automated unit test suite
└── target/                 # Compiled bytecode and packaged JAR binaries
```

---

## Build & Test Commands

```bash
# Clean workspace and compile source files
mvn clean compile

# Execute JUnit test suite
mvn test

# Package into executable JAR archive
mvn package
```
