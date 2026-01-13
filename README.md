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
<img width="1000" height="700" alt="image" src="https://github.com/user-attachments/assets/5fd33377-3f8f-43ab-ae44-4758a01c25a0" />


### 2. Greeting Endpoint (Default)
The initial implementation of the greeting endpoint without parameters.
- **URL**: `http://localhost:8080/greeting`
<img width="1000" height="700" alt="image" src="https://github.com/user-attachments/assets/c061f2ac-f754-4fa1-9618-eb2b3d8ab898" />


### 3. Greeting with Parameters
Testing the Custom Greeting (Dynamic)
- **URL**: `http://localhost:8080/greeting?name=Emil`
<img width="1000" height="700" alt="image" src="https://github.com/user-attachments/assets/47b48105-f0a8-48d0-9c5f-a1b9d38ab038" />


---

## 🚀 How to Run locally
1. Clone the repository.
2. Open the project in IntelliJ IDEA.
3. Run the `FirstProjectJavaSpringApplication.java` file.
4. Open your browser and navigate to `http://localhost:8080`.
