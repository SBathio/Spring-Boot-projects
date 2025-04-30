# Spring Boot Projects

A curated set of Spring Boot applications demonstrating key features of Java backend development, RESTful APIs, and modular architecture.

---

## 🚀 Features
- Create, retrieve, update, and delete (CRUD) operations on topics
- RESTful API endpoints using Spring Web
- Clean modular architecture: controller, service, repository layers
- Uses in-memory data store for simplicity and clarity

---

## 🔧 Tech Stack
- Java 17
- Spring Boot
- Maven
- Spring Data

---

## 📦 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/SBathio/Spring-Boot-projects.git
cd Spring-Boot-projects
```

### 2. Build the Project
```bash
mvn clean install
```

### 3. Run the Application
```bash
mvn spring-boot:run
```

The application will launch at:
```
http://localhost:8080
```

---

## 📂 Project Structure
```
src/
├── main
│   ├── java
│   │   └── io/sbathio/springbootprojects  # Application logic, controllers, services
│   └── resources
│       └── application.properties        # Configuration file
```

---

## 🧪 Example Usage
- **GET /topics**: Returns a list of topics
- **POST /topics**: Creates a new topic
- **PUT /topics/{id}**: Updates a topic by ID
- **DELETE /topics/{id}**: Deletes a topic

**Sample JSON Body for POST/PUT:**
```json
{
  "id": "spring",
  "name": "Spring Framework",
  "description": "Spring Boot project structure and basics"
}
```

---

## 📘 License
This project is open source and available under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author
**Sigou Bathily**  
[LinkedIn](https://www.linkedin.com/in/sbathily)  |  [GitHub](https://github.com/SBathio)

---

