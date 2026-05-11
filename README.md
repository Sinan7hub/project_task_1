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


<img width="949" height="599" alt="image" src="https://github.com/user-attachments/assets/49f2a8ee-4233-406c-a71a-29d2b5a2e4b2" />
