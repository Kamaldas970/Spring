# Spring IoC Layered Architecture Application

## Overview

This project demonstrates the implementation of Spring Framework's Inversion of Control (IoC) Container using XML-based configuration. The application follows a layered architecture consisting of Presentation, Service, and Repository layers.

## Technologies Used

* Java
* Spring Framework
* Maven
* Eclipse IDE

## Project Structure

### Web Layer

Handles user interactions and acts as the presentation layer.

### Service Layer

Contains business logic and processes requests from the web layer.

### Repository Layer

Responsible for data access operations and persistence-related functionality.

## Features

* XML-based Spring bean configuration
* Dependency Injection using Spring IoC Container
* Layered Architecture Design Pattern
* Loose Coupling between application components
* Easy maintainability and scalability

## Learning Objectives

* Understanding Spring IoC Container
* Bean Creation and Management
* Dependency Injection Concepts
* XML Configuration in Spring
* Layered Application Design

## Project Flow

1. Spring Container loads `Applicationconfig.xml`.
2. Bean definitions are created and managed by the IoC Container.
3. Dependencies are injected automatically.
4. Web Layer communicates with Service Layer.
5. Service Layer interacts with Repository Layer.
6. Application executes business operations.

## How to Run

1. Clone the repository.
2. Import the project into Eclipse.
3. Update Maven dependencies.
4. Run `LaunchAppmain.java`.
5. Verify bean creation and dependency injection through console output.

## Key Concepts Demonstrated

* Spring IoC (Inversion of Control)
* Dependency Injection (DI)
* Bean Lifecycle Management
* XML Bean Configuration
* Loose Coupling
* Layered Architecture

## Author

Kamaldas Balerao
B.Tech, Civil Engineering
Vardhaman College of Engineering
