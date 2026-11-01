# 🎓 E-Learning Management System

An interactive Java-based E-Learning Management System designed to create a centralized digital learning environment for students and teachers. The application provides a platform for sharing educational resources, conducting quizzes, submitting assignments, communicating through chat, and collaborating through peer reviews.

Built using Java Swing for the graphical user interface and MySQL for database management, the system aims to improve accessibility, communication, and collaboration in the learning process.

## 🚀 Features

### 👨‍🎓 Student Dashboard

* **User Authentication:** Secure login and registration with role-based access.
* **Learning Resources:** View and access educational materials uploaded by teachers.
* **Assignment Submission:** Submit assignments through file uploads.
* **Online Quizzes:** Attempt quizzes created by teachers.
* **Peer Review:** Review other students' assignments and provide feedback.
* **Chat System:** Communicate with teachers and other users.

### 👨‍🏫 Teacher Dashboard

* **Resource Management:** Upload and share educational materials.
* **Assignment Management:** View and access student-submitted assignments.
* **Quiz Creation:** Create quizzes with multiple-choice questions and correct answers.
* **Student Interaction:** Communicate with students through the chat functionality.

### 💬 Communication & Collaboration

* Integrated chat functionality.
* Peer-to-peer assignment feedback.
* Centralized educational resource management.

## 🛠️ Technologies Used

| Technology    | Purpose                      |
| ------------- | ---------------------------- |
| Java          | Core application development |
| Java Swing    | Graphical User Interface     |
| MySQL         | Database management          |
| JDBC          | Java-MySQL connectivity      |
| Maven         | Project and build management |
| IntelliJ IDEA | Development environment      |

## 🏗️ Project Structure

```text
E-Learning-System/
│
├── APP Project 3/
│   ├── pom.xml
│   │
│   ├── src/
│   │   └── main/
│   │       └── java/
│   │           ├── dashboard/
│   │           │   ├── Login.java
│   │           │   ├── RegistrationForm.java
│   │           │   ├── StudentDashboard.java
│   │           │   ├── TeacherDashboard.java
│   │           │   └── Chatbox.java
│   │           │
│   │           ├── database/
│   │           │   └── DBConnection.java
│   │           │
│   │           ├── Chatbox.java
│   │           ├── DatabaseConnection.java
│   │           └── FileUploader.java
│   │
│   └── APP Report.pdf
│
└── README.md
```

## ⚙️ Installation and Setup

### Prerequisites

* Java Development Kit (JDK 22)
* MySQL Server
* IntelliJ IDEA or another Java IDE
* Maven

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/E-Learning-System.git
```

### Step 2: Open the Project

Open the `APP Project 3` folder in IntelliJ IDEA.

### Step 3: Configure MySQL

1. Start your MySQL server.
2. Create a database named `elearning`.
3. Configure the database connection details in the database connection Java files.
4. Create the required database tables for users, uploaded files, assignments, quizzes, questions, responses, chats, and peer reviews.

### Step 4: Configure JDBC

Add the MySQL Connector/J dependency to the Maven configuration (`pom.xml`).

### Step 5: Run the Application

Run the following Java class to launch the login interface:

```text
dashboard.Login
```

Register as a student or teacher to explore the respective dashboards.

## 🎯 Project Objectives

* Develop a centralized platform for digital education.
* Simplify communication between students and teachers.
* Improve assignment submission and evaluation workflows.
* Enable interactive assessments through quizzes.
* Encourage collaborative learning through peer reviews.
* Demonstrate practical implementation of Java GUI development and database connectivity.

## 🔮 Future Enhancements

* Integration of video lectures and live classes.
* Automated quiz evaluation and performance analytics.
* Enhanced security with password hashing and secure authentication.
* Cloud-based storage for educational resources.
* Mobile application support.
* Improved notification and discussion systems.

## 👨‍💻 Contributors

This project was developed as a team-based academic mini project at SRM Institute of Science and Technology.

## 📌 Note

This repository was shifted from my college GitHub account to my personal GitHub account.

---

**If you find this project interesting, feel free to explore the repository!**
