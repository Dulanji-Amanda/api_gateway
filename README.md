# 🚪 API Gateway Service

## 📌 Project Overview
The API Gateway serves as the single entry point for all client requests in the TripDiary application. It routes incoming requests to the appropriate backend microservices, handles cross-origin resource sharing (CORS), and provides load balancing capabilities using Eureka.

---

## 🎯 Mandatory Information
- **Student Name**: Dulanji Amanda Sathsarani
- **Student Number**: 241722009
- **GCP Project ID**: project-00e6ad8d-07ac-4315-820

---

## 🛠 Technology Stack
- Java 25
- Spring Boot 3.4.x
- Spring Cloud Gateway
- Spring Cloud Netflix Eureka Client
- Spring Cloud LoadBalancer
- Maven
- Google Cloud Platform (GCP)
- PM2 (Process Manager)

---

## 🚀 Setup / Getting Started Instructions

### Prerequisites
- JDK 25 installed
- Maven installed
- Eureka Server and Config Server must be running

### Installation & Execution
1. Clone the repository and navigate to the directory:
   ```bash
   cd api-gateway
   ```
2. Build the project:
   ```bash
   mvn clean install
   ```
3. Run the application:
   ```bash
   mvn spring-boot:run
   ```
The gateway will start on port `8080`.
