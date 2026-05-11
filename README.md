# First Spring Boot Application

A Spring Boot project built with Java and Thymeleaf templating engine. This project demonstrates basic Spring MVC concepts with simple endpoints and dynamic HTML rendering.


## Tech Stack

- Java 17
- Spring Boot 4.0.5
- Spring MVC
- Thymeleaf (Server-side templating engine)
- Lombok
- Maven



---

## 🌐 Endpoints

### 1. Home Endpoint

```

GET /

```

Returns a simple text response:

```

Hello Vistula, in my first Spring Boot controller

```

---

### 2. Greeting Endpoint (Thymeleaf View)

```

GET /greeting

```

#### Query Parameters:
- `name` (optional, default: "World")

#### Example:
```

/greeting?name=Sinan

