# Cloud MySQL Project - Java 21

This project demonstrates saving and retrieving data using **Spring Boot**, **Hibernate**, and **MySQL** hosted on **Google Cloud Platform (GCP)**. The project uses **Java 21**.

---

## Demo Video

A short demonstration of the project can be viewed here:  
[Demo Video Link](https://drive.google.com/file/d/1098e8fS1O3YgKhBJ9gTBPYuYPmPtluST/view?usp=sharing)

---

## Features

- Save and retrieve data from a **Cloud SQL MySQL database**.
- Automatic database creation using **Hibernate**.
- Fully configured Spring Boot application with Java 21.
- Clean commit history showcasing development progress.

---

## Prerequisites

- **Java 21**
  ```bash
  java -version
---

## Update the **application.properties** file with your GCP MySQL details:

```spring.datasource.host=YOUR_PUBLIC_IP
spring.datasource.port=3306
spring.datasource.url=jdbc:mysql://${spring.datasource.host}:${spring.datasource.port}/courses?createDatabaseIfNotExist=true
spring.datasource.username=YOUR_DB_USERNAME
spring.datasource.password=YOUR_DB_PASSWORD

spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQLDialect
```

## Running The Project

- Backend: run `mvn -q -e -DskipTests package` at repo root to build services.
- Frontend: run `npm install` then `npm run dev` inside `frontend-app`.

## 
- Name  : Dasun Nirmal
- SID   : 2301671031
- Email : dasun200301@gmail.com
