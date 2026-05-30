# 💄 Beauty Bliss - E-Commerce Website

Beauty Bliss is a full-stack Django-based e-commerce platform for beauty and personal care products. The platform allows customers to browse products, manage carts and wishlists, place orders, make secure payments, and track their purchases.

## 🚀 Features

### 👤 User Features

* User Registration & Authentication
* Login / Logout System
* Password Reset & Change Password
* Customer Profile Management
* Multiple Shipping Addresses

### 🛍️ Product Features

* Browse Products by Categories
* Product Detail Pages
* Search Products
* Face Care Products
* Body Care Products
* Hair Care Products
* Makeup Products

### ❤️ Wishlist & Cart

* Add Products to Wishlist
* Remove Products from Wishlist
* Add Products to Cart
* Update Product Quantity
* Remove Products from Cart
* Real-Time Cart Total Calculation

### 💳 Order & Payment

* Secure Payment Integration using Razorpay
* Checkout System
* Order Placement
* Order Tracking
* Invoice Generation (PDF)
* Order History

### 📞 Customer Support

* Contact Us Form
* Return & Refund Policy Page
* Privacy Policy Page

### 🛠️ Admin Features

* Product Management
* Customer Management
* Order Management
* Payment Management
* Contact Message Management
* Django Admin Dashboard

---

## 🏗️ Tech Stack

### Frontend

* HTML5
* CSS3
* Bootstrap
* JavaScript

### Backend

* Python
* Django

### Database

* SQLite3

### Payment Gateway

* Razorpay

### PDF Generation

* ReportLab

---

## 📂 Project Structure

```bash
myproject/
│
├── myapp/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│   ├── templates/
│   ├── static/
│
├── media/
│   └── product/
│
├── manage.py
└── db.sqlite3
```

---

## 📊 Database Models

### Product

* Title
* Description
* Category
* Composition
* Selling Price
* Product Image

### Customer

* User
* Name
* Mobile Number
* Address
* State
* City
* Zip Code

### Cart

* User
* Product
* Quantity

### Wishlist

* User
* Product

### Payment

* User
* Amount
* Razorpay Payment Details

### OrderPlaced

* Customer
* Product
* Quantity
* Order Status
* Payment Details

### ContactMessage

* Name
* Email
* Phone
* Message

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/beauty-bliss.git
cd beauty-bliss
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows

```bash
venv\Scripts\activate
```

Linux/Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### Create Superuser

```bash
python manage.py createsuperuser
```

### Run Development Server

```bash
python manage.py runserver
```

Visit:

```text
http://127.0.0.1:8000/
```

---

## 🔐 Environment Variables

Create a `.env` file and add:

```env
SECRET_KEY=your_secret_key

RAZORPAY_KEY_ID=your_key_id

RAZORPAY_KEY_SECRET=your_key_secret
```

---

## 📸 Main Pages

* Home Page
* About Us
* Contact Us
* Product Categories
* Product Detail
* Cart
* Wishlist
* Checkout
* Orders
* Profile
* Login/Register
* Invoice Download

---

## 🎯 Future Enhancements

* Product Reviews & Ratings
* Coupon System
* Product Recommendations
* Email Notifications
* Inventory Management
* Multiple Payment Gateways
* Admin Analytics Dashboard
* AI Product Recommendation System

---

## 👨‍💻 Author

**Disha**

Frontend Developer | Django Developer | MERN Stack Learner

---

## 📄 License

This project is created for educational and portfolio purposes. Feel free to use and modify it for learning.
