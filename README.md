# Product Ordering App

## Overview
**Product Ordering App** is a microservices-based application developed with **Spring Boot**.  
It demonstrates a modular architecture where each service is responsible for a specific domain:

- **Product Service** → Manages product information and availability.  
- **Transaction Service** → Handles order creation and transaction processes.  
- **API Gateway** → Provides a single entry point to route requests to microservices.  

This project is designed as a learning/demo application to showcase the fundamentals of **microservices architecture**.

---

## Technologies
- Java 17  
- Spring Boot  
- Spring Cloud (API Gateway, Service Discovery, etc.)  
- Maven  
- Docker (optional)  

---

## Project Structure
```
product-ordering-app/
  ├── api-gateway/
  ├── product-service/
  ├── transaction-service/
  └── README.md
```


---

## Getting Started
1. Clone the repository:  
   ```bash
   git clone https://github.com/<your-username>/product-ordering-app.git
   ```

2. Navigate into each service and run with Maven:

  ```
    mvn spring-boot:run 
  ```

3. Access services via the API Gateway endpoint.
