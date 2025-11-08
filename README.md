# ⚡ Learning Spring Boot — REST API with MySQL & Aiven

A minimal yet mighty **Spring Boot CRUD API** built while diving into backend development.  
Connects to a **MySQL database hosted on Aiven**, keeps secrets safe via `.env`, and serves clean JSON endpoints.  
Because learning Java should *feel powerful*, not painful. 💪

---

## 🧩 Tech Stack
- ☕ **Java 17**
- 🌱 **Spring Boot 3**
- 🧠 **Spring Data JPA**
- 🐬 **MySQL (Aiven Cloud)**
- ⚙️ **Maven**
- 🧾 **Dotenv (for environment variables)**

---

## 📂 Project Structure
```

Learning-Springboot/
├── src/
│   ├── main/
│   │   ├── java/com/example/demo/
│   │   │   ├── MainController.java      # REST endpoints
│   │   │   ├── User.java                # Entity class
│   │   │   └── UserRepository.java      # Database access layer
│   │   └── resources/
│   │       └── application.properties   # Uses .env variables
│   └── test/
├── .env                                 # Environment variables (ignored in .git)
├── .gitignore
└── pom.xml

```

---

## ⚡ Quick Start

### 1️⃣ Setup `.env`
Create a file named `.env` in the project root:
```

DB_USERNAME=avnadmin
DB_PASSWORD=your_aiven_password
DB_URL=jdbc:mysql://mysql-learning-springboot-arnavtrivediofficial.i.aivencloud.com:20248/defaultdb?ssl-mode=REQUIRED

````

### 2️⃣ Run it
```bash
mvn spring-boot:run
````

Your API lives at 👉 `http://localhost:8080`

---

## 🔥 API Endpoints

| Method | Endpoint    | Description    |
| ------ | ----------- | -------------- |
| POST   | `/demo/add` | Add a new user |
| GET    | `/demo/all` | Get all users  |

---

## 🧠 Fun Fact

This repo once leaked an Aiven password...
Now it’s *the poster child for secure Spring Boot setups* 😎

---

## 👨‍💻 Author

**Arnav Trivedi**
🎓 Vellore Institute of Technology
💡 Exploring Full Stack, AI/ML & Cloud
🌐 [GitHub](https://github.com/4rnav-here)

---

⭐ *Star this repo if you love clean code and caffeine-powered learning!*

```

---

Would you like me to add a **badge header** (like Spring Boot 🌱 | MySQL 🐬 | Java ☕) to give it a sleek “open-source project” vibe? It looks great on GitHub repo pages.
```
