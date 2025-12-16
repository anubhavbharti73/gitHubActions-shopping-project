🛒 GitHub Actions Shopping Project

A full-stack Shopping / E-Commerce web application designed to demonstrate CI/CD automation using GitHub Actions, along with modern frontend and backend development practices.

This repository showcases how application code, pipelines, and automation come together in a real-world DevOps workflow.

📌 Project Overview

This project consists of:

Frontend: Angular-based shopping UI

Backend: Spring Boot REST APIs

Database: Embedded H2 (for simplicity)

CI/CD: GitHub Actions pipelines for build & automation

The main goal of this project is to demonstrate GitHub Actions in action while working with a real application, not just sample pipelines.

Key Features

Shopping cart functionality

Product listing and management

RESTful backend APIs

GitHub Actions CI pipelines

Docker-ready structure

Automated build and test execution

Tech Stack
Category	Technology
Frontend	Angular
Backend	Spring Boot (Java)
Database	H2
Build Tools	Maven, npm
CI/CD	GitHub Actions
Containerization	Docker (optional)
📂 Repository Structure
gitHubActions-shopping-project/
│
├── ShopCartH2/        # Spring Boot backend
├── Shopping/          # Angular frontend
├── .github/workflows/ # GitHub Actions pipelines
└── README.md

Prerequisites

Make sure the following are installed on your system:

Java 8+

Maven

Node.js & npm

Angular CLI

Git (Docker optional)

Running the Application Locally
Clone the Repository
git clone https://github.com/anubhavbharti73/gitHubActions-shopping-project.git
cd gitHubActions-shopping-project

Start Backend (Spring Boot)
cd ShopCartH2
./mvnw spring-boot:run


Backend will be available at:
http://localhost:8080

Start Frontend (Angular)

Open a new terminal:

cd Shopping
npm install
ng serve


Frontend will be available at:
http://localhost:4200

GitHub Actions CI/CD

This repository uses GitHub Actions to automate:

Application build

Dependency installation

Unit test execution

CI validation on pull requests

All workflows are located in:

.github/workflows/


This setup demonstrates real CI/CD integration with application code, making it ideal for DevOps learning and interviews.

Docker Support (Optional)

You can containerize the application using Docker (if configured):

docker compose up --build

Contributing

Contributions are welcome!

Fork the repository

Create a feature branch

Commit your changes

Open a Pull Request

Please ensure code quality and pipeline stability before submitting.

License

This project is licensed under the MIT License.

📬 Contact

If you have questions, suggestions, or improvements, feel free to open an issue or contribute directly.
