# 🚀 UserDemo – Enterprise Spring Boot REST API

## 📌 Project Overview
**UserProfile Management** is a backend application built using **Spring Boot 3.4.6** and **Java 21**.  
The project demonstrates clean architecture principles, RESTful API development, database integration using JPA, and modern backend best practices.

This application showcases hands-on experience in:

- REST API development  
- ORM using Hibernate & JPA  
- MySQL database integration  
- Maven-based project management  
- Layered architecture (Controller → Service → Repository)  

---

## 🏗️ Architecture

The project follows a standard layered architecture:

- **Controller Layer** → Handles HTTP Requests
- **Serveice Interface Layer** → Have a Imlmentated mehods from the controller 
- **Service Implementation Layer** → Business Logic  
- **Repository Layer** → Database Interaction  
- **Entity Layer** → JPA Entities
- **Exception Layer** → Exceptions Classes
- **Exception Handler** → Exception Handler Classes
- **Utility** → Helper Classes

---

## 🛠️ Technology Stack

### 🔹 Backend
- Java 21  
- Spring Boot 3.4.6  
- Spring Web (REST APIs)  
- Spring Data JPA  
- Hibernate (JPA Implementation)  

### 🔹 Database
- MySQL  
- MySQL Connector/J  

### 🔹 Build & Dependency Management
- Maven  

### 🔹 Development & Testing
- Spring Boot DevTools  
- Spring Boot Starter Test (JUnit, Mockito)  

---

## 📦 Maven Dependencies

```xml
<dependencies>

    <!-- Spring Data JPA for ORM -->
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-data-jpa</artifactId>
    </dependency>

    <!-- Spring Web for REST APIs -->
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-web</artifactId>
    </dependency>

    <!-- Developer Tools -->
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-devtools</artifactId>
        <scope>runtime</scope>
        <optional>true</optional>
    </dependency>

    <!-- MySQL Driver -->
    <dependency>
        <groupId>com.mysql</groupId>
        <artifactId>mysql-connector-j</artifactId>
        <scope>runtime</scope>
    </dependency>

    <!-- Testing Framework -->
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-test</artifactId>
        <scope>test</scope>
    </dependency>

</dependencies>
```

---

## ⚙️ Build Plugin

```xml
<build>
    <plugins>
        <plugin>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-maven-plugin</artifactId>
        </plugin>
    </plugins>
</build>
```

---

## ▶️ How to Run the Application

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/UserDemo.git
```

### 2️⃣ Navigate to project directory

```bash
cd UserDemo
```

### 3️⃣ Configure MySQL in `application.properties`

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_database
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```

### 4️⃣ Run the application

```bash
mvn spring-boot:run
```

Application will start at:

```
http://localhost:8080
```

---

## 📈 Key Backend Concepts Demonstrated

- ✔ RESTful API Design  
- ✔ Dependency Injection  
- ✔ JPA Entity Mapping  
- ✔ Repository Pattern  
- ✔ Exception Handling  
- ✔ Maven Dependency Management  
- ✔ Database Configuration  

---

## 👨‍💻 Author

**Saisuhas Y**  
Backend Developer | Java | Spring Boot | Hibernate | JPA | MySQL  

---

⭐ If you found this project useful, feel free to star the repository.
