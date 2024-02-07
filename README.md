# Microservices Project Overview

## Project Description

This microservices project is designed to provide a scalable and secure solution for handling user-related operations, hotel information, and ratings. The system is implemented using Spring Boot, and various microservices interact with each other to achieve the desired functionality.

## Key Features

### User Service:
- Manages user-related operations.
- Implements security features using Spring Security and Okta for user authentication and authorization.
- Utilizes FeignClient and RestTemplate for communication with other services.
- Integrates with Eureka Server for service discovery.

### Hotel Service:
- Handles hotel information.
- Utilizes FeignClient and RestTemplate for communication with other services.
- Implements circuit breaker using Resilience4J for enhanced fault tolerance.
- Integrates with Eureka Server for service discovery.

### Rating Service:
- Manages hotel ratings.
- Utilizes FeignClient and RestTemplate for communication with other services.
- Implements circuit breaker using Resilience4J for enhanced fault tolerance.
- Integrates with Eureka Server for service discovery.

### Configuration Management:
- Utilizes GitHub Config Server for storing and managing common configurations.

### API Gateway:
- Configures multiple URLs and routes requests to the appropriate microservices.
- Enhances security and monitoring at the gateway level.

### Service Discovery:
- Utilizes Eureka Server for service registration and discovery.

### Circuit Breaker:
- Implements circuit breaker patterns using Resilience4J to enhance system resilience.

### Retry Mechanism:
- Integrates retry mechanisms to handle transient failures and improve overall reliability.

### Rate Limiter:
- Implements rate limiting for controlling the rate of incoming requests.

## Technologies Used
- **Spring Boot:** A powerful framework for building microservices in Java.
- **FeignClient and RestTemplate:** Used for making requests and handling communication between microservices.
- **Eureka Server:** Enables service registration and discovery.
- **GitHub Config Server:** Manages and stores common configurations.
- **API Gateway:** Configures and routes requests to the appropriate microservices.
- **Resilience4J:** Implements circuit breaker patterns for fault tolerance.
- **Spring Security and Okta:** Ensures secure communication within the microservices ecosystem.

## Contributing
Feel free to contribute to this project by opening issues or submitting pull requests. Your feedback and contributions are highly appreciated!
