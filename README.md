# Java HTTP Requests Application

A simple Java application that demonstrates how to perform HTTP requests using various techniques (e.g., `HttpURLConnection`, third-party libraries like Apache HttpClient or OkHttp).

---

## ✨ Features

- Make HTTP `GET`, `POST`, and other requests
- Read responses from remote APIs
- Parse JSON or plain-text responses
- Optional: send headers, payload, and manage timeouts
- Useful for learning and testing REST API communication in Java

---

## 🛠️ Prerequisites

- Java 8+ (JDK)
- Maven (recommended)
- Internet connection (for testing external APIs)

---

## 📦 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Rossi2882/Requests.git
cd Requests
```

### 2. Build the Project

If you're using Maven:

```bash
mvn clean install
```

If not using Maven, ensure all required libraries (if any) are added manually to your classpath.

### 3. Run the App

```bash
java -jar target/Requests.jar
```

Or run from your IDE (e.g., IntelliJ, Eclipse).

---

## 🧭 Project Structure

```
src/
├── main/
│   └── java/
│       └── requests/            # Main logic (e.g., HttpClientExample.java)
├── resources/                   # (Optional) config files or test data
└── pom.xml                      # Maven dependencies and project setup
```
