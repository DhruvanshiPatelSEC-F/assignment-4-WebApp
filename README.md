# RESTful Client Integration using Spring RestTemplate

## 📌 Project Overview

This project is a Spring Boot application that consumes an external REST API using RestTemplate. It demonstrates how to perform GET, POST, PUT, and DELETE operations and expose custom endpoints.

---

## 🌐 API Used

* JSONPlaceholder
* Base URL: https://jsonplaceholder.typicode.com

---

## ⚙️ Technologies Used

* Java 17
* Spring Boot 3.x
* Maven
* RestTemplate
* Lombok
* Postman

---

## 🚀 How to Run the Project

1. Open the project in IntelliJ IDEA
2. Make sure Java 17 is installed
3. Build the project using Maven
4. Run the main class:
   RestclientApplication.java
5. The application will start on:
   http://localhost:8080

---

## 🔗 Available Endpoints

### 1. Get All Posts

GET /api/posts

### 2. Get Post by ID

GET /api/posts/{id}

### 3. Create Post

POST /api/posts

Request Body:
{
"userId": 1,
"title": "Test Title",
"body": "Test Body"
}

### 4. Update Post

PUT /api/posts/{id}

### 5. Delete Post

DELETE /api/posts/{id}

---

## 🔄 Sample Request & Response

### GET /api/posts/1

Response:
{
"userId": 1,
"id": 1,
"title": "sample title",
"body": "sample body"
}

---

## 📊 Features Implemented

* Consumed external REST API using RestTemplate
* Created custom REST endpoints
* Mapped JSON response to Java objects (POJO)
* Performed CRUD operations (GET, POST, PUT, DELETE)
* Implemented logging for requests and responses

---

## 🧪 Testing

All endpoints were tested using Postman.

---

## 📸 Screenshots

(Add screenshots of Postman requests and responses here)

---

## ⚠️ Notes

* JSONPlaceholder does not persist data, so POST, PUT, and DELETE are simulated.
* Logging is implemented using Logger in the service layer.

---
