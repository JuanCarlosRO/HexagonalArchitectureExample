# HexagonalArchitectureExample
Self study about hexagonal architecture implemented in java, example provided by ChatGpt with self notes.

Hexagonal architecture structure example:
src/main/java/com/empresa/proyecto
├── domain/              <-- Bussines kernel
│   ├── model/           <-- Domain entities (POJO's)
│   ├── ports/           <-- Interfaces (in and out ports)
│   └── service/         <-- Use cases / Bussines logic
│
├── application/         <-- logic cordination and DTOs (opcional)
│
├── infrastructure/      <-- External implementations
│   ├── repository/      <-- Out adapters (ej. JPA)
│   ├── config/          <-- Beans, configuration
│   └── controller/      <-- In adapters (ej. REST)
│
└── ProyectoApplication.java

This projects is a basic well-documented example of how to implement hexagonal architecture, it was created based on chatGPT examples and responses.

The porpouse of this repository is to grow and explain the most characteristics of this architecture.

Autor: Juan Robledo.


