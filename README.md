# First Spring Boot Application

A Spring Boot project built with Java and Thymeleaf templating engine.

## Tech Stack

- **Java 17**
- **Spring Boot 4.0.5**
- **Thymeleaf** - Server-side templating
- **Spring MVC** - Web framework
- **Lombok** - Reduce boilerplate code
- **Maven** - Build management

## Project Structure

```
src/
├── main/
│   ├── java/        # Java source code
│   └── resources/   # Application properties and templates
└── test/            # Test files
```

## Building & Running

### Prerequisites
- Java 17 or higher
- Maven (or use the included `mvnw` wrapper)

### Build
```bash
./mvnw clean package
```

### Run
```bash
./mvnw spring-boot:run
```

## Dependencies

- **spring-boot-starter-thymeleaf** - Template engine for dynamic web pages
- **spring-boot-starter-webmvc** - Spring MVC web framework
- **lombok** - Code generation for getter/setter and other boilerplate
- **Testing dependencies** - JUnit 5 and Spring Test

## License

Not specified

---

*Last Updated: 2026-05-11*
