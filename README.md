# Java Development Environment Setup

Toolchain verification for a Java and Maven development environment.

## What it does

A minimal project confirming that a Java development setup is correctly configured — the
JDK resolves, Maven builds, and the JUnit test harness runs. It's the smoke test you run
before trusting a new machine or a fresh install.

```
src/main/java/com/comp301/a00setup/GFG.java       minimal application class
src/test/java/com/comp301/a00setup/AppTest.java   harness verification
pom.xml                                            Maven build and dependency configuration
```

## Running it

Requires Java 17+ and Maven.

```bash
mvn clean test
```

A passing build confirms the toolchain is ready.
