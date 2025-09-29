#  Car Rental Service (Spring Boot)

A **Spring Boot REST API** for managing a simple **Car Rental System**.  
Provides endpoints for customers, vehicles, and booking lifecycle, with MySQL integration and H2 support for development/testing.  

---

##  Features
- Customer management (CRUD)  
- Vehicle management (CRUD + availability)  
- Booking workflow (reserve, return, conflict validation)  
- MySQL database integration with Spring Data JPA  
- Validation & global exception handling  
- RESTful endpoints with JSON responses  

---

##  Tech Stack
- **Backend:** Java 17, Spring Boot, Spring Data JPA, Hibernate  
- **Database:** MySQL (H2 in-memory for testing)  
- **Tools:** Maven, Postman, Git, IntelliJ IDEA  
- **Testing:** JUnit, Mockito  

---

##  Getting Started

### Clone the repository
```bash
git clone https://github.com/ldogan/car-rental-springboot.git
cd car-rental-springboot
