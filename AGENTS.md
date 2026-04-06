# AGENTS.md

## Project Overview
This project is a Spring Boot application with a simple structure. It includes basic Java classes and a Maven build system. The main components are:

- **Main.java**: Entry point of the application, containing the `main` method.
- **CartEntity.java** and **OrderEntity.java**: Represent data models for a cart and an order, respectively.

## Build and Run

### Build
The project uses Maven for dependency management and builds. To compile the project, run:

```bash
mvn clean compile
```

### Run
To execute the application, use:

```bash
mvn exec:java -Dexec.mainClass="org.example.Main"
```

### Test
Currently, there are no test files in the `src/test/java` directory. Add test cases to ensure code quality.

## Code Conventions

- **Package Structure**: All Java files are under `org.example`.
- **Entities**: Classes like `CartEntity` and `OrderEntity` are simple POJOs (Plain Old Java Objects) with private fields.
- **Main Class**: Contains the `main` method for application execution.

## Key Files

- `pom.xml`: Maven configuration file specifying project metadata and dependencies.
- `src/main/java/org/example/Main.java`: Application entry point.
- `src/main/java/org/example/CartEntity.java`: Represents a cart entity.
- `src/main/java/org/example/OrderEntity.java`: Represents an order entity.

## Notes for AI Agents

- Follow the Maven build lifecycle for compiling and running the project.
- Add test cases in `src/test/java` to improve code coverage.
- Maintain the existing package structure when adding new classes.
- Use the `pom.xml` file to manage dependencies.

## Future Enhancements

- Add database integration for persisting `CartEntity` and `OrderEntity`.
- Implement REST APIs for CRUD operations on entities.
- Introduce logging for better debugging and monitoring.
