# Quiz Application  

A **robust and interactive Quiz Application** built with **ReactJS, Spring Boot, JPA, and MySQL**. This project ensures **secure data management**, **user authentication**, and **data validation**, providing an efficient and engaging user experience.  

## Features  
- ✅ **User Authentication** – Secure login and registration.  
- ✅ **Quiz Management** – Create, edit, and delete quizzes dynamically.  
- ✅ **Validation & Security** – Backend validation for input data.  
- ✅ **ReactJS UI** – Modern frontend with interactive elements.  
- ✅ **Role-Based Access** – Admins can manage quizzes; users can take quizzes.  

## Tech Stack  
- **Frontend**: ReactJS, Bootstrap  
- **Backend**: Spring Boot, Spring Security, JPA  
- **Database**: MySQL  
- **Validation**: Java Bean Validation (Hibernate Validator)  

## Installation  

### 1. Clone the Repository  
```
git clone https://github.com/chandramohan0/QuizApplication
cd QuizApplication
cd server
```

### 2. Configure Database
Update the **application.properties** file with your MySQL credentials:
```
#MYSQL DATABASE CONFIGURATIONS
spring.datasource.url=jdbc:mysql://localhost:3306/quizapplication
spring.datasource.username=root
spring.datasource.password=root@123
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver

#HIBERNATE CONFIGURATIONS
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

### 3. Run the Backend
```
cd
mvn spring-boot:run
```

### 4. Access the Backened
Backend will run on  **http://localhost:8080/**.

### 5. Run the Frontend
```
cd client
npm install
npm start
```

### 5. Access the Frontend of Application
Open **http://localhost:3000/** in your browser.
