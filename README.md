# 🚀 DevConnect Backend

[![Java](https://img.shields.io/badge/Java-17-blue?logo=java)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.1.0-brightgreen?logo=springboot)](https://spring.io/projects/spring-boot)
[![Build](https://img.shields.io/badge/Build-Maven-blue?logo=apachemaven)](https://maven.apache.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **DevConnect** is a RESTful backend for a developer networking platform, enabling secure authentication, real-time messaging, and social content sharing.

---

## 📂 Project Overview

DevConnect Backend serves as the engine behind a developer-focused platform. It offers:

- 🔐 **JWT-based authentication**
- 🧾 **User registration and login**
- 📝 **Posting and retrieving public developer posts**
- 💬 **Direct messaging between users**
- 🧰 **Spring Boot + JPA + Security integration**
- 🔄 **MySQL (prod) and H2 (test) support**

---

<details>
<summary>📌 Tech Stack</summary>

- **Java 17**
- **Spring Boot 3.1.0**
- **Spring Security**
- **Spring Data JPA**
- **JWT (jjwt 0.9.1)**
- **MySQL & H2 Database**
- **Maven**
- **Lombok**
</details>

---

## ⚙️ Setup & Installation

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/devconnect-backend.git
cd devconnect-backend

# 2. Configure database in src/main/resources/application.properties

# 3. Build the project
mvn clean install

# 4. Run the application
mvn spring-boot:run
