# Vistula University - Spring Boot REST API (Task 1)

This project documents the initial setup and environment configuration for a Java Spring Boot application. Task 1 focuses on creating a base controller and verifying server communication via HTTP requests.

## 🛠️ Environment & Setup
- **Framework**: Spring Boot 3.x
- **Build Tool**: Maven
- **Language**: Java 17
- **Server**: Embedded Tomcat (Port 8080)

## 📡 Initial Controller Testing
In this task, I implemented a `GreetingController` to test the basic Request Mapping and parameters.

### 1. Base Endpoint
Testing the root URL to ensure the Spring Boot server is responding correctly to web requests.
- **URL**: `http://localhost:8080/`
<img width="1000" height="700" alt="Screenshot 2026-01-07 103201" src="https://github.com/user-attachments/assets/ff725698-c05c-4798-87e7-d9b35b0f5e35" />


### 2. Greeting Endpoint (Default)
The initial implementation of the greeting endpoint without parameters.
- **URL**: `http://localhost:8080/greeting`
<img width="1000" height="700" alt="Screenshot 2026-01-07 103255" src="https://github.com/user-attachments/assets/664907da-e65b-47ff-b475-bfaaade23813" />


### 3. Greeting with Parameters
Testing the Custom Greeting (Dynamic)
- **URL**: `http://localhost:8080/greeting?name=Emil`
<img width="1000" height="700" alt="Screenshot 2026-01-07 103343" src="https://github.com/user-attachments/assets/abb70911-608a-478b-8c1f-566e97302d29" />


---

## 🚀 How to Run locally
1. Clone the repository.
2. Open the project in IntelliJ IDEA.
3. Run the `FirstProjectJavaSpringApplication.java` file.
4. Open your browser and navigate to `http://localhost:8080`.
