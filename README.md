# OnlineFoodOrder
## This is My opening UI
![Screenshot (1)](https://github.com/Anishhkumarr/OnlineFoodOrder/assets/144413430/79ab42b0-f131-4605-b245-31f08bf340e5)

# This is My Ordering content
![Screenshot (2)](https://github.com/Anishhkumarr/OnlineFoodOrder/assets/144413430/2fb1de84-ded6-4fef-a7ba-e2cfae9b276d)
# 🍔 Online Food Ordering System

A web-based **Online Food Ordering System** developed using PHP and MySQL to provide a platform for customers to browse food items, manage their cart, place orders, and make payments.

The system also provides a **manager/restaurant module** for managing food items and processing customer orders.

---

## 🌐 Project Overview

The **Online Food Ordering System** is designed to simplify the food ordering process by connecting customers with restaurants through a web-based application.

The application provides separate functionality for:

* 👤 Customers
* 🏪 Restaurant/Managers
* 🍔 Food Item Management
* 🛒 Shopping Cart
* 📦 Order Management
* 💳 Payment
* 🔐 Login & Registration

---

## 🚀 Features

### 👤 Customer Module

* Customer registration
* Customer login
* Browse available food items
* Add food items to cart
* Update cart items
* Place food orders
* View order information
* Payment functionality
* Customer logout

### 🏪 Manager Module

* Manager registration
* Manager login
* Manage restaurant information
* Add food items
* Edit food items
* Delete food items
* View food items
* View customer orders
* Update order status

### 🛒 Shopping Cart

Customers can:

* Add food items
* Update quantities
* Remove items
* Review their order before checkout

### 📦 Order Management

The system provides functionality for managing customer orders from the restaurant/manager side.

Managers can view order details and update order status.

### 💳 Payment

The application includes payment-related functionality for processing customer orders.

---

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap
* Font Awesome

### Backend

* PHP

### Database

* MySQL

### Development Environment

* XAMPP
* Apache
* phpMyAdmin
* Visual Studio Code

---

## 📂 Project Structure

```text
OnlineFoodOrder/
│
├── css/
│   └── CSS stylesheets
│
├── js/
│   └── JavaScript files
│
├── images/
│   └── Food and UI images
│
├── Fontawesome/
│   └── Font Awesome resources
│
├── index.php
├── aboutus.php
├── contactus.php
│
├── customersignup.php
├── customerlogin.php
├── login_u.php
├── logout_u.php
│
├── managersignup.php
├── managerlogin.php
├── login_m.php
├── logout_m.php
│
├── add_food_items.php
├── add_food_items1.php
├── edit_food_items.php
├── delete_food_items.php
├── delete_food_items1.php
├── view_food_items.php
├── foodlist.php
│
├── cart.php
├── update-cart.php
├── COD.php
├── payment.php
├── onlinepay.php
│
├── view_order_details.php
├── orders-update.php
│
├── myrestaurant.php
├── myrestaurant1.php
│
├── connection.php
├── session_m.php
├── session_u.php
│
└── foodorder.sql
```

The repository currently contains separate PHP files for customer authentication, manager authentication, food management, cart operations, order processing, and payment functionality.

---

## ⚙️ How to Run the Project Locally

### 1. Install XAMPP

Install **XAMPP** with:

* Apache
* MySQL
* phpMyAdmin

### 2. Clone the Repository

```bash
git clone https://github.com/Anishhkumarr/OnlineFoodOrder.git
```

### 3. Move the Project to XAMPP

Copy the project into:

```text
C:\xampp\htdocs\OnlineFoodOrder
```

### 4. Start XAMPP

Open the XAMPP Control Panel and start:

```text
Apache
MySQL
```

### 5. Create the Database

Open:

```text
http://localhost/phpmyadmin
```

Create a MySQL database.

Then import:

```text
foodorder.sql
```

The repository includes the SQL database file required by the application.

### 6. Configure Database Connection

Open:

```text
connection.php
```

Update the database credentials according to your local MySQL configuration.

Example:

```php
$host = "localhost";
$username = "root";
$password = "";
$database = "foodorder";
```

### 7. Run the Application

Open:

```text
http://localhost/OnlineFoodOrder/
```

---

## 🔄 Application Workflow

```text
                    ONLINE FOOD ORDERING SYSTEM
                              │
             ┌────────────────┴────────────────┐
             │                                 │
        👤 CUSTOMER                       🏪 MANAGER
             │                                 │
       Register/Login                    Register/Login
             │                                 │
       Browse Food Items                 Manage Food Items
             │                                 │
       Add to Cart                       View Orders
             │                                 │
       Place Order                       Update Orders
             │                                 │
       Make Payment                      Restaurant Management
             │
             ▼
        Order Database
             │
             ▼
       Restaurant/Manager
```

---

## 📸 Screenshots

### 🏠 Home Page

```text
![Screenshot (1)](https://github.com/Anishhkumarr/OnlineFoodOrder/assets/144413430/79ab42b0-f131-4605-b245-31f08bf340e5)
```
# This is My Ordering content
![Screenshot (2)](https://github.com/Anishhkumarr/OnlineFoodOrder/assets/144413430/2fb1de84-ded6-4fef-a7ba-e2cfae9b276d)
### 🍔 Food Items

```text
Add your food listing screenshot here
```

### 🛒 Shopping Cart

```text
Add your cart screenshot here
```

### 👤 Customer Login

```text
Add your customer login screenshot here
```

### 🏪 Manager Dashboard

```text
Add your manager dashboard screenshot here
```

### 📦 Order Management

```text
Add your order management screenshot here
```

---

## 🎯 Project Objectives

The main objectives of this project are:

* To provide an online platform for ordering food.
* To simplify the food ordering process.
* To allow customers to browse and select food items.
* To provide shopping cart functionality.
* To manage customer orders digitally.
* To provide restaurant/manager functionality for managing food items.
* To maintain food and order information using a MySQL database.

---

## 🔐 Authentication

The system provides separate authentication functionality for:

### Customer

```text
Registration → Login → Browse Food → Cart → Order → Payment
```

### Manager

```text
Registration → Login → Manage Food → View Orders → Update Orders
```

---

## 📊 Database

The project uses **MySQL** as its database.

The database structure and required SQL scripts are included in:

```text
foodorder.sql
```

Database connectivity is handled through PHP using the project's database connection file.

---

## 🔮 Future Enhancements

Possible improvements include:

* Online payment gateway integration
* Restaurant location and map integration
* Food search and advanced filtering
* Food ratings and reviews
* Order tracking
* Email/SMS notifications
* Customer order history
* Responsive mobile-first UI
* REST API integration
* Admin analytics dashboard
* Role-based access control
* Password hashing and improved authentication security

---

## 👨‍💻 Developer

### Anish Kahar

**MCA Student | Full Stack Developer**

**Technologies:**
`Java` `Spring Boot` `Angular` `JavaScript` `PHP` `SQL` `MySQL`

🌐 **Portfolio:**
https://anish-kahar-portfolio.vercel.app/

💻 **GitHub:**
https://github.com/Anishhkumarr

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

---

## 📄 License

This project was developed for **educational and portfolio purposes**.
