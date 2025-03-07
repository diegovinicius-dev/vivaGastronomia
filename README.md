<!-- Header Image (substitua o link abaixo pelo seu logotipo, se tiver) -->
<p align="center">
  <img src="https://via.placeholder.com/600x150?text=VivaGastronomia" alt="VivaGastronomia Logo">
</p>

<!-- Badges -->
<p align="center">
  <a href="https://github.com/diegovinicius-dev/vivagastronomia">
    <img src="https://img.shields.io/badge/build-passing-brightgreen" alt="Build Status">
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License">
  </a>
  <a href="https://openjdk.java.net/">
    <img src="https://img.shields.io/badge/Java-21-blue" alt="Java Version">
  </a>
  <a href="https://github.com/diegovinicius-dev/vivagastronomia/stargazers">
    <img src="https://img.shields.io/github/stars/diegovinicius-dev/vivagastronomia?style=social" alt="GitHub Stars">
  </a>
</p>

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
vivagastronomia/
├── src/
│   ├── main/
│   │   ├── java/com/seunome/vivagastronomia/
│   │   │   ├── controller/         # REST Controllers
│   │   │   ├── service/            # Business logic
│   │   │   ├── repository/         # Data access layers
│   │   │   ├── model/              # Domain models / Entities
│   │   │   └── dto/                # Data Transfer Objects
│   │   └── resources/
│   │       ├── application.properties
│   │       └── ...                 # Other resource files
│   └── test/
│       └── java/...                # Test classes
├── pom.xml
└── README.md

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
