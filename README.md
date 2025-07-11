# GameZone360
GameZone-360 -Game Parlour &amp; cafe management system
> A full-stack applicaton to manage bookings, cafe orders, billing, and real-time updates for a mordern game parlour and cafe setup.
----
## Project Overview 
GameZone 360 is a cloud -ready, microservice-based web app built with Java 21, Spring Boot, Angular 17, Kafka, and AW. It handles everything from gamestation bookings to cafe ordering, billing, and real-time notifications- all through an interactive and mordern UI.
-----
## Tech Stack
|Layer            | Technology                        |
|-----------------|-----------------------------------|
|Frontend         | Angular 17, Tailwind css, RxJs    |
|Beckend          | Java 21, SpringBoot(Microsevices) |
|Messaging        | Apache Kafka                      |
|Database         | PostgreSQL, MongoDB               |
|Auth             | Spring Security + JWT             |
|Cloud            | AWS(EC2, RDS, S3, API Gateway)    |
|Dev Tools        | Docker, Postman, GitHub Actions   |

-------
## Project Structure
""bash
gamezone-360
|-Backend/
|    |- user-service/
|    |- game-sevice/
|    |- cafe-service/
|    |- billing-service/
|    |- notification-service/
|    |- gateway-service/
|-Frontend
     |-angular-app/
-------
## Run Configuration
# Backend

# User Service
cd backend/user-service
./mvnw spring-boot:run 
# Game Service
cd ../game-service
./mvnw spring-boot: run 
# Cafe Service
cd ../cafe-service
./mvnw spring-boot: run 
# Billing Service
cd ../billing-service
./mvnw spring-boot:run 
# Notification Service
cd ../mvnw spring-boot:run 
# Gateway Service
./mvnw spring-boot:run 

# Frontend

cd frontend/angular-app
npm install
ng serve --open

# Health Check URLs
User Service: http://localhost:8081/actuator/health
Game Service: http://localhost:8082/actuator/health
Cafe Service: http://localhost:8083/actuator/health
Billing Service: http://localhost:8084/actuator/health
Notification Service: http://localhost:8085/actuator/health
API Gateway: http://localhost




