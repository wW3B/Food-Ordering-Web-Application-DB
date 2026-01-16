### 🍽️ Food Ordering Web Application (Node.js & MySQL)

This project is a database-driven web application for food ordering and user management.
The system allows users to register, log in, browse food items, add them to a cart, and view their personal information.

### 🧩 System Overview

The application is built using Node.js, EJS, and MySQL, following a client–server architecture.
Frontend pages interact with backend logic and database operations to provide dynamic content and user authentication.

### 🔁 Application Flow
index.js
   ↓
login-register.ejs
   ↓
server.js
   ↓
home.ejs ⇄ product.ejs
   ↓
database.js (MySQL)

### 📌 Flow Description

- index.js acts as the entry point of the application

- Users start at the login/register page

- After authentication, requests are handled by server.js

- User data and product data are retrieved from MySQL via database.js

- Users can view their profile or order food

### 📄 Page Descriptions
## 🔐 login-register.ejs

# Purpose:
Allows users to register or log in to the system

# Main Features:

- User registration with name, email, and password

- User login authentication

- Form validation and data submission to backend

# Technologies Used:
Node.js, HTML, CSS, JavaScript, Bootstrap, MySQL

### 🛒 product.ejs

# Purpose:
Allows users to browse food items, view prices, and place orders

# Main Features:

- Display food menu with images and prices

- Food selection and ordering

- Payment workflow logic

# Technologies Used:
Node.js, HTML, CSS, JavaScript, Bootstrap

### 👤 home.ejs

# Purpose:
Displays personal information of the logged-in user

# Main Features:

- Display user profile information (name, email)

- Retrieve user data dynamically from database

# Technologies Used:
HTML, CSS, JavaScript, Bootstrap

### 🗄️ Database Structure (MySQL)
## 📦 Tables Overview
# 🛍️ carts

- Stores food items added to the shopping cart

- Used to manage user orders before checkout

# 🍔 product

- Stores information about food items available in the store

- product_name – name of the product

- product_price – price of the product

- product_image – image of the product

- product_status – availability status of the product

# 👥 users

- Stores customer information

- users_name – customer name

- users_email – customer email

- users_phone – customer phone number

- users_password – encrypted user password

# 🛠️ Technologies Used

- Backend: Node.js

- Frontend: HTML, CSS, JavaScript, Bootstrap

- Template Engine: EJS

- Database: MySQL

# 🎯 Key Learning Outcomes

- Implemented user authentication with database integration

- Designed dynamic web pages using EJS templates

- Connected frontend, backend, and database layers

- Practiced CRUD operations with MySQL

- Understood full web application request–response flow
