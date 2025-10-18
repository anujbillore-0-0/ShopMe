# 🛒 Shopme – E-Commerce Electronics Store

**Shopme** is a full-stack e-commerce web application built using modern Java and Spring technologies.  
It provides a complete online shopping experience for customers and a powerful administration dashboard for managing the store, products, and sales.

---

## 🚀 Project Overview

Shopme enables users to browse and purchase electronics through a secure, intuitive, and responsive interface.  
It supports multiple user roles — **customers** and **administrators** — each with distinct privileges and workflows.

---

## 👥 User Roles & Features

### 🔧 Administrator

- 🧑‍💼 **User Management** – Manage admin users and access permissions.  
- 🛠️ **Product Management** – Add, edit, or delete products, categories, and brands.  
- 👥 **Customer Management** – View and manage customer details.  
- 📦 **Order Management** – Process and track customer orders.  
- 🚚 **Shipping & Payments** – Configure shipping options and payment gateways.  
- 📊 **Sales Reports** – Generate and visualize detailed analytics.  
- 💬 **Reviews & Questions** – Moderate product reviews and customer inquiries.  
- ⚙️ **Settings** – Configure store and system settings.  

### 🛍️ Customer

- 🔍 **Product Browsing** – Explore or search products by category.  
- 🧾 **Product Details** – View detailed information, specs, and reviews.  
- 🛒 **Shopping Cart** – Add or remove items and view order summary.  
- 💳 **Checkout** – Secure checkout process integrated with **PayPal**.  
- 🚚 **Order Tracking** – Track order status and view order history.  
- 👤 **Account Management** – Register, login (including Google/Facebook), and manage profile.  

---

## 🧠 Tech Stack

### 🖥️ Backend
- Java  
- Spring Boot  
- Spring Data JPA & Hibernate  
- Spring Security & OAuth2 (Google & Facebook Login)  
- Spring Mail  
- RESTful Web Services  
- JUnit, AssertJ, Mockito (Testing)  

### 🎨 Frontend
- Thymeleaf  
- Bootstrap 4  
- jQuery  
- HTML5  

### 🗄️ Database & Cloud
- MySQL 8.0  
- Amazon S3 (for file storage)  
- Heroku (for deployment)  

### 💳 Payments & Reporting
- PayPal Checkout API  
- Google Chart API (for sales reports)  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/AAdewunmi/Shopme-ECommerce-Application.git
cd Shopme-ECommerce-Application
````

### 2️⃣ Configure the Database

Create a **MySQL** database and update credentials in `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/shopme_db
spring.datasource.username=your_username
spring.datasource.password=your_password
```

### 3️⃣ Build and Run

```bash
mvn clean install
mvn spring-boot:run
```

### 4️⃣ Access the Application

* **Admin Panel:** [http://localhost:8080/ShopmeAdmin](http://localhost:8080/ShopmeAdmin)
* **Customer Storefront:** [http://localhost:80](http://localhost:80)

---

## ☁️ Deployment

Shopme is structured for deployment on:

* **Heroku** → for web hosting
* **Amazon S3** → for static file and image storage

Ensure environment variables are properly configured for database credentials, mail service, and PayPal integration before deployment.

---

## 🖼️ Demo Screenshots

### 👤 Customer Interface

| Page                 | Screenshot                                  |
| -------------------- | ------------------------------------------- |
| **Login Page**       | ![Customer Login](<img width="1507" height="777" alt="customer_login" src="https://github.com/user-attachments/assets/767dffc8-6373-4e6e-b892-85b3b2ad06a8" />
)       |
| **Landing Page**     | ![Customer Landing](<img width="1917" height="577" alt="customer_landing_page" src="https://github.com/user-attachments/assets/9e9f498b-73a3-4646-819d-0f582819cd8f" />
)   |
| **Shopping Cart**    | ![Customer Cart](<img width="1905" height="633" alt="customer_shopping_cart" src="https://github.com/user-attachments/assets/5816fbf0-56e2-4666-a957-efed2fe583e8" />
)         |
| **Checkout Page**    | ![Customer Checkout](<img width="1898" height="645" alt="customer_checkout" src="https://github.com/user-attachments/assets/91fcfe7f-6be2-4bea-96c1-320a287cf9a0" />
) |
| **Order Management** | ![Customer Orders](<img width="1886" height="877" alt="customer_manage_orders" src="https://github.com/user-attachments/assets/c907b5f7-3c05-42ea-a7d3-5d7e973e3581" />
)     |

---

### 🧑‍💼 Administrator Interface

| Page                  | Screenshot                                |
| --------------------- | ----------------------------------------- |
| **Login Page**        | ![Admin Login](admin-login.png)           |
| **Dashboard**         | ![Admin Dashboard](admin-dashboard.png)   |
| **Manage Brands**     | ![Admin Brands](admin-brands.png)         |
| **Manage Categories** | ![Admin Categories](admin-categories.png) |
| **Manage Customers**  | ![Admin Customers](admin-customers.png)   |
| **Manage Products**   | ![Admin Products](admin-products.png)     |
| **Manage Users**      | ![Admin Users](admin-users.png)           |
| **Site Settings**     | ![Admin Settings](admin-settings.png)     |

---

## 🤝 Contribution

Contributions are always welcome!
To contribute:

1. **Fork** the repository
2. **Create** a new branch (`git checkout -b feature/your-feature`)
3. **Commit** your changes (`git commit -m "Add new feature"`)
4. **Push** to your branch (`git push origin feature/your-feature`)
5. **Open a Pull Request**

For major changes, please open an issue to discuss your ideas before implementing them.

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

## 👨‍💻 Author

Developed and maintained by **Anuj Billore**
📧 *[[your-email@example.com](mailto:your-email@example.com)]*
🌐 *[https://your-portfolio-link.com](https://your-portfolio-link.com)*

---

⭐ **If you like this project, don’t forget to give it a star!**

```

---

Would you like me to add **technology badges** at the top (like “Built with Spring Boot”, “Uses MySQL”, “PayPal Integration”, etc.) to make it look more professional for GitHub and portfolio viewers?
```
