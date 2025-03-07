# VivaGastronomia

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/diegovinicius-dev/vivagastronomia)
[![Version](https://img.shields.io/badge/version-0.1.0-blue)](https://github.com/diegovinicius-dev/vivagastronomia)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Java Version](https://img.shields.io/badge/Java-21-blue)](https://openjdk.java.net/)
[![GitHub Stars](https://img.shields.io/github/stars/diegovinicius-dev/vivagastronomia?style=social)](https://github.com/diegovinicius-dev/vivagastronomia)

*An intelligent backend system providing personalized healthy recipe recommendations.*

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [Author](#author)

## Overview

VivaGastronomia delivers tailored recipe suggestions based on users' dietary preferences and restrictions. Leveraging AI-driven insights, it aims to enhance healthy eating habits and support personalized nutrition.

## Features

- **User Management**: Register, update, and manage user profiles including dietary preferences and restrictions.
- **Recipe CRUD**: Create, read, update, and delete healthy recipes.
- **Personalized Recommendations**: Generate tailored recipe suggestions using AI-powered insights.
- **Interactive API Documentation**: Auto-generated documentation via Swagger UI.

## Tech Stack

- **Java 21** with **Spring Boot 3.x**
- **Spring Web** & **Spring Data JPA**
- **Lombok** to reduce boilerplate code
- **H2 Database** for development
- **Maven** for dependency management
- **Springdoc OpenAPI UI** for API documentation

## Project Structure

The project is organized as follows:
```
vivagastronomia/
├── src/
│   ├── main/
│   │   ├── java/com/seunome/vivagastronomia/
│   │   │   ├── controller/         # REST Controllers
│   │   │   ├── service/            # Business logic
│   │   │   ├── repository/         # Data access layer
│   │   │   ├── model/              # Domain models / Entities
│   │   │   └── dto/                # Data Transfer Objects (if needed)
│   │   └── resources/
│   │       └── application.properties
│   └── test/                     # Unit and integration tests
├── pom.xml                       # Maven configuration
└── README.md                     # Project documentation
```

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push your branch (`git push origin feature/your-feature`).
5. Open a pull request for review.

## Author

**Diego Vinicius Duarte Cavalcante**  
- [LinkedIn](https://www.linkedin.com/in/diego-cavalcante-tech/)  
- [GitHub](https://github.com/diegovinicius-dev)  
- Email: diegocavalcante.tech@gmail.com
