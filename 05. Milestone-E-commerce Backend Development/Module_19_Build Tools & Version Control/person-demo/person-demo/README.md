# Person Demo - Spring Boot Maven Project

This project was created for Module 19 Assignment.

## Commands Used

### Git Commands

```bash
git init
git add .
git commit -m "Init"
git remote add origin https://github.com/YOUR_USERNAME/person-demo.git
git branch -M main
git push -u origin main

git add .
git commit -m "Add Person class with basic fields and methods"
git push

git add README.md
git commit -m "Add README with command history"
git push
```

### Maven Build Command

```bash
mvn clean package
```

## How to Run the Project

```bash
mvn spring-boot:run
```

## Project Structure

- `src/main/java/com/example/persondemo/Person.java` – contains the Person entity.
- `pom.xml` – Maven configuration.