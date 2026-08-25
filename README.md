# AI-Driven Adaptive Login Fraud Detection and Risk Scoring System

**Course:** SOA PROGRAMMING AND MICROSERVICES (24SDCS03)  
**Academic Year:** 2026 - 2027  

## Team Members
- **Ch. Aditya** (2420030669)
- **A. Aaryan** (2420090098)
- **K. Gokul** (2420030716)

**Guide:** Mary Navyatha Govindu

---

## Abstract

Fraudulent login attempts are a major cybersecurity concern in modern web applications, where attackers may gain unauthorized access by using stolen credentials, unfamiliar devices, unusual locations, or abnormal login behavior. Conventional authentication mechanisms primarily depend on usernames, passwords, and fixed security rules, which may not be sufficient to identify sophisticated or continuously evolving login threats. Therefore, there is a need for an intelligent and adaptive system that can analyze login behavior and dynamically determine the risk associated with each authentication attempt.

The proposed AI-Driven Adaptive Login Fraud Detection and Risk Scoring System aims to detect suspicious login activities by analyzing behavioral and contextual characteristics associated with user authentication. The system collects relevant login attributes such as login time, device information, IP address, location, failed login attempts, and historical login patterns. These attributes are processed to identify deviations from normal user behavior. A machine learning-based anomaly detection approach is incorporated to classify login attempts and generate a fraud risk score ranging from low to critical risk.

## Service-Oriented Architecture (SOA) & Microservices

The proposed system follows a Service-Oriented Architecture using independent microservices to provide modularity, scalability, maintainability, and secure communication between components. The major services include:

- **Authentication Service:** Manages user registration, secure login, JWT-based authentication, and role-based authorization.
- **Fraud and Risk Analysis Service:** Evaluates login behavior and communicates with the machine learning model to calculate the risk score. Based on the risk level, the system dynamically allows a low-risk login, requests additional verification for a medium-risk login, or blocks and reports a high-risk login.
- **Alert and Notification Service:** Manages suspicious-login alerts.
- **Security Analytics Service:** Provides administrators with a centralized dashboard for monitoring authentication activities and security events.

## Technologies Used

The system is implemented using modern microservices technologies including:
- **Backend Framework:** Spring Boot
- **API Gateway:** Spring Cloud Gateway
- **Service Discovery:** Eureka Service Registry
- **Authentication:** JWT (JSON Web Tokens), REST APIs
- **Architecture:** Database-per-service architecture
- **AI/ML:** Machine learning components for anomaly detection and feature selection (e.g., Oppositional Aquila Optimization Algorithm, Deep Belief Network, Gated Recurrent Unit).

## Quality Assurance & DevOps
API testing, unit testing, integration testing, security analysis, and CI/CD practices are incorporated to improve the reliability and security of the application. The proposed approach aims to provide a more intelligent alternative to static authentication mechanisms by enabling adaptive security decisions based on the real-time risk associated with each login attempt.
