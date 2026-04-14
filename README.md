A backend-based Quiz Application built using Spring Boot that provides REST APIs to manage questions and quizzes. The system allows creation of question banks, quiz generation based on categories, and dynamic quiz retrieval.

	🚀 Features

✅ CRUD operations for Questions

✅ CRUD operations for Quizzes

✅ Generate quizzes based on category

✅ Fetch questions dynamically for a quiz

✅ RESTful API design

✅ Layered architecture (Controller → Service → Repository)


      🛠️ Tech Stack
Language: Java
Framework: Spring Boot
Database: MySQL
ORM: Spring Data JPA / Hibernate
Tools: Postman, Git

	📂 Project Structure	

quiz-application-backend/
│
├── controller/     # Handles HTTP requests

├── service/        # Business logic

├── repository/     # Database interaction

├── model/          # Entity classes

└── application.properties
	
	🔄 Workflow
Admin adds questions with:
Category
Options
Correct answer
Quiz is created based on category.
When user requests a quiz:
Questions are fetched dynamically from DB
Quiz is served via API

	💡 Key Concepts Used
REST API Design
MVC Architecture
Dependency Injection
JPA & Hibernate
Database Mapping (Entities & Relationships)

🧪 Testing
APIs tested using Postman
Verified CRUD operations and data flow
