# Job Portal Web App

A Spring Boot-based web application for job seekers and employers.

## Features

- User registration & authentication (job seekers & employers)
- Job posting and management (employers)
- Job search and application (job seekers)
- Admin dashboard for managing users and jobs

## Tech Stack

- **Backend:** Spring Boot, Spring Security, JPA/Hibernate
- **Frontend:** Thymeleaf, Bootstrap
- **Database:** MySQL

## Getting Started

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/jobportal.git
    cd jobportal
    ```

2. **Configure the database:**
    - Update `src/main/resources/application.properties` with your MySQL credentials.

3. **Build and run:**
    ```bash
    mvn spring-boot:run
    ```

4. **Access the app:**
    - Visit `http://localhost:8080`

## Folder Structure

- `src/main/java` - Java source code
- `src/main/resources/templates` - Thymeleaf templates
- `src/main/resources/static` - Static assets (CSS, JS)

## License

This project is licensed under the MIT License.