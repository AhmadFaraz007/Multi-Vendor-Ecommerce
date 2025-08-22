# 👗 AvenueFashion - PHP + MySQL eCommerce Website

**AvenueFashion** is a dynamic and fully functional eCommerce web application built using **PHP** and **MySQL**, developed by **Taha Jamil** as a student of **Web Technologies** and **Database Systems** at **COMSATS University Vehari**.

This project includes a complete shopping experience for customers and a powerful admin control panel to manage the store’s backend operations.

---

## 📌 Features

### 🧑‍💻 Customer Side (Front-End)
- Browse products by categories and brands
- Product search and filtering
- User registration and login system
- Add to cart and place orders
- View order history
- Profile and account management

### 🔐 Admin Control Panel (Back-End)
- Secure admin authentication
- Admin dashboard to manage:
  - Products
  - Categories
  - Brands
  - Orders
  - Registered customers
- Ability to create new admin accounts

---

## 🚀 Getting Started

### ✅ Prerequisites
Make sure the following software is installed:

- [XAMPP](https://www.apachefriends.org/index.html) (includes Apache, MySQL, PHP)

### 🛠 Installation Steps

1. **Download & Install XAMPP**

2. **Place the Project in `htdocs` Directory**
   - Copy the project folder `AvenueFashion` into:
     ```
     C:\xampp\htdocs\
     ```

3. **Create the Database**
   - Start Apache and MySQL from the XAMPP Control Panel
   - Open your browser and go to:  
     [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
   - Create a new database named:
     ```
     ecom_store
     ```

4. **Import the SQL File**
   - In phpMyAdmin, select the `ecom_store` database
   - Click on **Import**
   - Select the SQL file located at:
     ```
     C:\xampp\htdocs\AvenueFashion\ecom_store.sql
     ```
   - Click **Go** to import the database

---

## 🌐 How to Access the Application

### 🛍 Customer Site:
Visit in your browser:

(http://localhost/AvenueFashion/index.php)




### 🛠 Admin Dashboard:
Visit in your browser:

(http://localhost/AvenueFashion/admin_area/index.php?dashboard)



---

## 🔑 Login Credentials

### 👤 Sample Customer Account
- **Email**: taha@gamil.com  
- **Password**: 1234

> Customers can also register new accounts via the website.

### 👮 Admin Account
- **Email**: admin@admin.com  
- **Password**: 1234

> New admin users can be created from within the admin dashboard.

---

## 📁 Project Structure Overview

AvenueFashion/ <br>
├── admin_area/         # Admin dashboard functionality <br>
├── customer/           # Customer account pages <br>
├── includes/           # Reusable components like database connection and functions <br>
├── product_images/     # Uploaded product images <br>
├── ecom_store.sql      # Database SQL file for setup <br>
├── index.php           # Homepage of the customer-facing site<br>
└── .htaccess           # Apache config for clean URLs (optional) <br>




---

## 📚 About the Developer

**Ahmad Faraz**  
Student of Web Technologies and Database Systems  
**COMSATS University Vehari**

---

## 📬 Feedback & Contributions

This project was developed for academic and learning purposes.  
Feel free to use it, learn from it, and improve upon it.

If you encounter bugs or have ideas for improvement, contributions are always welcome!

---

