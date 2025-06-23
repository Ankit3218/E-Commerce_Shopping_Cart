# 🛒 E-Commerce Shopping Cart

A simple full-stack e-commerce shopping cart built using **Spring Boot**, **Spring MVC**, **Thymeleaf**, **Spring Data JPA**, and **MySQL**.

---

##  Features

1 Product listing for users  
2 Add to Cart and Checkout flow  
3 Admin Panel for managing products (CRUD)  
3 Modular layered architecture (Controller → Service → Repository)  
4 Image upload and display support  
5 Responsive UI using Bootstrap 5  
6 Session-based shopping cart

---

## Technologies Used

- Java 17+
- Spring Boot 3.x
- Spring MVC
- Spring Data JPA (Hibernate)
- Thymeleaf
- MySQL
- Bootstrap 5
- HTML/CSS

---

## 🗂 Project Structure

src
├── main
│ ├── java
│ │ └── com.ecommerce
│ │ ├── controller
│ │ ├── model
│ │ ├── service
│ │ └── repository
│ └── resources
│ ├── static
│ │ └── image
│ ├── templates
│ │ ├── admin
│ │ └── user
│ └── application.properties




---

## ⚙ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YourUsername/E-Commerce_Shopping_Cart.git
cd E-Commerce_Shopping_Cart


2. Configure MySQL
Update your application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
server.port=8080 // you can set your own port number


3. Run the application
You can run it from your IDE or via the command line:
./mvnw spring-boot:run



🔐 Admin Panel:
URL: http://localhost:8080/admin/products
Features: Add, Edit, Delete Products
File Upload: Supports image path and upload to /image/ directory



📁 Sample Images:
Place sample product images inside:
src/main/resources/static/image/
Use filenames like fan.jpg, chair.png, etc.


🧪 Sample User Flow:
1.User visits / to view all products
2.User adds items to cart
3.Proceeds to /cart and clicks Checkout
4.Confirmation message is shown
5.Admin can manage products via /admin/products

✍️ Author
Ankit Kanojiya
GitHub: @Ankit3218
Project Status: ✅ Completed and Resume-ready









