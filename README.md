# Arena Booking System  

![Project Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)  
![Technologies](https://img.shields.io/badge/Technologies-Java%2C%20Spring%20Boot%2C%20MySQL%2C%20MongoDB%2C%20Angular%2C%20Docker-blue.svg)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)  

## 📋 Overview  

The **Arena Booking System** is a robust, scalable web platform built using microservices architecture designed to manage arena bookings for various events. Users can search for available arenas, view schedules, and make bookings. Administrators can manage arenas, handle booking conflicts, and generate reports. The platform integrates with **Razorpay** for payment processing and uses **MongoDB** for flexible data management.  

This system leverages key microservices principles such as **API Gateway**, **role-based access control**, **multithreading**, and **scalability** to handle high traffic efficiently. Backend services are deployed in **Docker containers** to ensure portability, scalability, and consistency across environments.

---

## 🚀 Features  

### User Features:  
- **Browse and search for arenas** based on location, type, and availability.  
- **Real-time arena availability check** for instant booking decisions.  
- **Book, modify, or cancel bookings** with a seamless workflow.  
- **View booking history** to track past reservations.  
- **Payment Integration**: Process payments securely through **Razorpay**.  

### Admin Features:  
- **Add, update, or remove arenas** from the system.  
- **Manage booking requests** and resolve conflicts efficiently.  
- **Generate detailed reports** on arena usage and booking trends.  

### Advanced Features:  
- **Role-Based Access Control (RBAC)**: Users have different levels of access, ensuring secure operation for both admins and regular users.  
- **API Gateway**: A single entry point for all services, managing traffic and enhancing security.  
- **Authentication & Authorization (JWT)**: Secure login for users and admins, preventing unauthorized access.  
- **Multithreading**: Support for handling concurrent requests, ensuring high performance in a multi-user environment.  
- **Notifications**: Real-time updates for booking confirmations, cancellations, and reminders.  
- **Scalable Architecture**: Built with Docker and microservices for scalability and fault tolerance.  
- **MongoDB Integration**: Stores flexible, non-relational data for quick access and efficient management.  
- **Razorpay Integration**: Handles secure payment processing for arena bookings.

---

## 🛠️ Technologies  

### Backend:  
- **Java Spring Boot** for building microservices-based RESTful APIs.  
- **MySQL** for managing relational data with Hibernate ORM.  
- **MongoDB** for flexible, non-relational data storage (for certain services).  
- **Spring Security** for robust authentication and role-based authorization.  
- **API Gateway** (using Spring Cloud Gateway) for routing requests to respective microservices.  
- **RabbitMQ/Kafka** (optional for asynchronous messaging) for inter-service communication.  
- **Razorpay** for payment gateway integration to handle secure payments.  

### Frontend:  
- **Angular** for a dynamic and responsive user interface, with components for booking management, schedules, and user interaction.  

### Other Tools:  
- **Docker** for containerizing each microservice and managing multi-container applications using Docker Compose.  
- **Swagger** for API documentation, providing an interactive and self-updating guide to all API endpoints.  

---

## 📑 API Documentation  

API documentation is available via Swagger.  
- After running the application, access the documentation at `http://localhost:8080/swagger-ui.html`.

---

## ⚙️ Installation  

### Prerequisites:  
- **Java 11+**  
- **Docker & Docker Compose**  
- **MySQL** (if running outside of Docker)  
- **MongoDB** (configured for services that require non-relational data storage)  

### Steps to Run Locally:  

1. **Clone the repository:**  
   ```bash  
   git clone https://github.com/yourusername/arena-booking-system.git  
   cd arena-booking-system
