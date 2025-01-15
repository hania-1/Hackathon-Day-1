# Hackathon-Day-1

# E-Commerce Platform Database Schema  

## 📌 Project Overview  
This project is part of the **Marketplace Builder Hackathon 2025** and focuses on designing a robust and scalable **database schema** for an E-commerce platform. The schema forms the backbone of an online marketplace, enabling seamless operations like product management, order processing, and customer interactions.  

---

## 📂 Schema Details  

### 1️⃣ **Users**  
- `user_id`: Unique identifier for each user.  
- `name`: Full name of the user.  
- `email`: Contact email address.  
- `password`: Encrypted password for account security.  
- `role`: Role of the user (e.g., admin, customer).  

### 2️⃣ **Products**  
- `product_id`: Unique identifier for each product.  
- `name`: Product name.  
- `description`: Detailed description of the product.  
- `price`: Price of the product.  
- `stock`: Available quantity.  
- `category_id`: Reference to product categories.  

### 3️⃣ **Orders**  
- `order_id`: Unique identifier for each order.  
- `user_id`: Reference to the user placing the order.  
- `order_date`: Date and time of the order.  
- `status`: Current status (e.g., pending, shipped, delivered).  

### 4️⃣ **Payments**  
- `payment_id`: Unique identifier for each payment.  
- `order_id`: Reference to the associated order.  
- `payment_method`: Payment method used (e.g., credit card, PayPal).  
- `status`: Payment status (e.g., successful, failed).  

### 5️⃣ **Reviews**  
- `review_id`: Unique identifier for each review.  
- `user_id`: Reference to the user who wrote the review.  
- `product_id`: Reference to the product being reviewed.  
- `rating`: Numeric rating (e.g., 1-5).  
- `comment`: User feedback.  

---

## 🚀 Key Features  
- Comprehensive schema for managing users, products, orders, payments, and reviews.  
- Scalable and efficient structure for real-world E-commerce platforms.  
- Designed with best practices for data normalization and integrity.  

---

## 🛠️ Tools Used  
- **Paper & Pencil**: For initial brainstorming and schema design.  
- **GitHub**: To document and share the project.  

---

## 📥 How to Use  
1. Clone the repository to your local machine:  
   ```bash
   git clone https://github.com/yourusername/ecommerce-schema.git
