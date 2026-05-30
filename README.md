# Advance-Chatting-Platform
# Fireball – Advanced Chatting Platform

A real-time chat application built using **Java Spring Boot**, and **MySQL** to provide seamless communication between users. The platform supports user interactions, instant messaging, friend requests, and persistent message storage.

## Features

* Real-time messaging using WebSocket
* User authentication and account management
* Private chat functionality
* Friend request system
* Message storage and retrieval
* Responsive frontend integration
* Database-driven architecture using MySQL

---

## Tech Stack

### Backend

* Java 21
* Spring Boot
* Spring Web

### Database

* MySQL

### Frontend

* HTML
* CSS
* JavaScript

### Build Tool

* Maven

---

## Project Structure

```plaintext
backend/
│
├── src/
│   ├── main/
│   │   ├── java/com/fireball/backend/
│   │   │   ├── AuthController.java
│   │   │   ├── MessageController.java
│   │   │   ├── FriendRequestController.java
│   │   │   ├── ChatWebSocketHandler.java
│   │   │   ├── WebSocketConfig.java
│   │   │   ├── User.java
│   │   │   ├── Message.java
│   │   │   └── BackendApplication.java
│   │   │
│   │   └── resources/
│   │       ├── static/
│   │       └── application.properties
│
├── pom.xml
└── README.md
```

---

## Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/your-username/fireball-chat-platform.git
```

### 2. Navigate to Project

```bash
cd backend
```

### 3. Configure MySQL Database

Create a database:

```sql
CREATE DATABASE fireball;
```

Update `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/fireball
spring.datasource.username=your_username
spring.datasource.password=your_password
```

### 4. Run Application

Linux / Mac:

```bash
./mvnw spring-boot:run
```

Windows:

```bash
mvnw.cmd spring-boot:run
```

Application runs at:

```plaintext
http://localhost:8080
```

---

## API & Real-Time Communication

### REST APIs

* User operations
* Authentication
* Friend requests
* Message management

### WebSocket

Supports real-time communication between connected users.

---

## Future Improvements

* Group chat support
* Media and file sharing
* End-to-end encryption
* Voice and video calling
* Push notifications
* Online/offline status tracking

---

## Author

**Sourik Paul**

LinkedIn:
[www.linkedin.com/in/sourik-paul-30516537](http://www.linkedin.com/in/sourik-paul-30516537)
