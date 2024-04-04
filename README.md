# Tollrate Microservices Application

This project is a Spring Boot-based microservices application for managing toll rates.

## Overview

The Tollrate application is designed to demonstrate the use of Spring Boot in creating microservices. It includes several services that work together to provide a comprehensive toll rate management system.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Java Development Kit (JDK)
- Maven
- Docker (for containerization)


## Architecture

The application is composed of several microservices, each responsible for a specific piece of functionality within the toll rate management system. The services communicate with each other using RESTful APIs and are orchestrated using the following components:

- **Service Discovery**: Allows services to find and communicate with each other without hard-coded hostnames and ports.
- **Config Server**: Centralizes external configuration management across all services in the microservices architecture.


## Installation

To install the Tollrate application, follow these steps:

1. Clone the repository:
git clone https://github.com/mounirrouissi/tollrate-app.git

## Running the Application

To run the individual services 

cd [service-name] then run:
./mvnw spring-boot:run

