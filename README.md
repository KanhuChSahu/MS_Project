# MS_Project: Microservices-Based E-Commerce Platform

## Project Overview
This project demonstrates a scalable, cloud-ready microservices architecture for an e-commerce ecosystem. It decouples core business logic into specialized services to ensure high availability, maintainability, and independent scalability.

## Architecture
The system is divided into three primary modules:
- **UserAuthService**: Manages user identity, secure authentication, and JWT-based authorization.
- **ProductCatalogService**: Handles product lifecycle management, categories, and inventory data.
- **ProductCatalogServiceProxy**: Acts as an API Gateway/Proxy layer to manage inter-service communication and external request routing.

## Tech Stack
- **Backend:** Java 17+, Spring Boot 3.x
- **Data Access:** Spring Data JPA, Hibernate
- **Security:** Spring Security, JSON Web Tokens (JWT)
- **Database:** MySQL (Production), H2 (Testing)
- **Integration:** Razorpay Payment Gateway API
- **Testing:** JUnit 5, Mockito, AssertJ

## Key Features
- **Secure Authentication:** Robust user login and registration with encrypted password storage.
- **Catalog Management:** RESTful APIs for managing complex product hierarchies.
- **Payment Integration:** Secure checkout flow using Razorpay.
- **Schema Validation:** Automated database schema verification using JdbcTemplate in test suites.

## Getting Started

### Prerequisites
- JDK 17 or higher
- Maven 3.6+
- MySQL Server

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/KanhuChSahu/MS_Project.git](https://github.com/KanhuChSahu/MS_Project.git)
Navigate to a service directory (e.g., UserAuthService):

Bash
cd UserAuthService_Dec2024
Build the project:

Bash
mvn clean install
Run the application:

Bash
mvn spring-boot:run
API Documentation
Once the services are running, you can access the Swagger UI (if enabled) or use Postman to interact with the endpoints at localhost:8080.


---

### Step 2: Clean up the Repository
To ensure acceptance, perform these "housekeeping" tasks in your Git terminal:

1.  **Remove Non-Project Files:** Delete any practice files (like `Rectangle.java` or `Square.java`) that are not part of the Microservices app.
2.  **Update the Default Branch:** Make sure your latest code is on the `dev` branch (which you are currently using) or merge it into `main`.
3.  **Check `.gitignore`:** Ensure you are not uploading your `/target/` folders or local IDE files (`.idea`, `.vscode`).

### Step 3: Fix the First Two Pages of the Report
Since the rejection mentioned the first two pages specifically, here is the visual checklist:

* **Page 1 (Title):** Ensure the "WOOLF/" and "SCALER" logos are exactly as shown in the template. The text "The project report of Kanhu Charan Sahu is approved..." must be at the **very bottom** of Page 1, not at the top of Page 2.
* **Page 2 (Certification):** This page should start with the word **CERTIFICATION** centered at the top. Ensure there is no other text from the title page bleeding onto this page.
* **Page Numbers:** Ensure your page numbering starts correctly (usually the Title Page is page 1, but some templates prefer the Table of Contents to be where numbering starts—check the template provided in `project_MS_report.pdf` carefully).

**Final Tip:** Your report is currently **20 pages**, but the instructions state a **minimum of 40 pages**. While the formatting is the primary reason for rejection now, increasing the depth of your "Implementation" and "Testing" sections will prevent a second rejection for "lack of breadth."
