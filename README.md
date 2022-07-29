# Cinema shop

## Project description
This application simulates cinema's ticket-reservation system and has nex features:
- Add/get movies
- Add/get cinema halls
- Add/get/find movie session
- Add/find user
- Add movie session to user's shopping cart
- Create order from user's shopping cart

## Project architecture
1. Application for testing 
2. Service - Application layer
3. DAO - Data access layer

## Database structure
![diagram](project_uml.png)

# Technologies used in project
- Java v.11
- Apache Maven v.3.8
- MySQL v.8
- Hibernate v.5

## How to run a project?
1. Clone this project
2. Install and configure MySQL
3. Open project in IntelliJ IDEA
4. Setup database parameters in `src/main/resources/hibernate.cfg.xml`
5. Run `src/main/java/mate/academy/Main.java`