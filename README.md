# 🛒 Ecommerce Web Application  

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)  
[![Django](https://img.shields.io/badge/Django-3.x-green.svg)](https://www.djangoproject.com/)  
[![Database](https://img.shields.io/badge/SQLite-Default-lightgrey.svg)](https://www.sqlite.org/)  
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  


A full-stack **Django-based E-commerce platform** that allows users to browse products, manage carts and wishlists, place orders, and maintain profiles. The project includes authentication, admin functionality, and dynamic product management.

---

## 📖 Features
- 👤 **User Authentication** – signup, login, profile management, password recovery  
- 🛍️ **Product Management** – browse, filter, and view details of products  
- 🛒 **Shopping Cart & Wishlist** – add/remove products, adjust quantities  
- 💳 **Checkout & Orders** – place orders with order tracking and status updates  
- 📩 **Contact & Feedback** – customers can submit feedback and contact queries  
- 📦 **Admin Panel** – manage products, categories, customers, and orders  
- 🎨 **Responsive UI** – built with HTML, CSS, JS for a smooth user experience  

---

## 🏗️ Project Structure
Ecommerce/
├── Eshop/ # Project-level settings, URLs, WSGI/ASGI
├── store/ # Main app (models, views, templates, urls)
│ ├── models/ # Models: Product, Category, Customer, Orders, Feedback
│ ├── views/ # Views: Home, Cart, Orders, Signup, Login, Profile, etc.
│ ├── templates/ # HTML templates (product, cart, login, signup, etc.)
│ ├── static/ # CSS, JS, images
│ ├── migrations/ # Database migrations
│ └── ...
├── uploads/ # Uploaded product images
├── db.sqlite3 # SQLite database
├── manage.py # Django management script
└── README.md


---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+  
- Django 3.x+  
- Virtualenv (recommended)

### Installation
```bash
# Clone repository
git clone https://github.com/your-username/Ecommerce.git
cd Ecommerce

# Create virtual environment
python -m venv env
source env/bin/activate   # On Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py makemigrations
python manage.py migrate

# Create superuser for admin
python manage.py createsuperuser

# Start server
python manage.py runserver

⚙️ Tech Stack

Backend: Django (Python)

Frontend: HTML, CSS, JavaScript

Database: SQLite (default, can be switched to PostgreSQL/MySQL)

Deployment Ready: Supports Gunicorn/Daphne with Nginx for production

🔮 Future Enhancements

Integration with payment gateways (Stripe, Razorpay, PayPal)

Recommendation system for personalized shopping

Advanced search & filtering with Elasticsearch

REST API endpoints for mobile app integration

Docker containerization for deployment

# 📸 Screenshots

### Homepage
![Homepage](https://github.com/user-attachments/assets/2967e2e8-55b0-42ef-9de6-c1434a4c46df)

### Product Page
![Product](https://github.com/user-attachments/assets/3a6b1479-7053-459b-8a90-c18cf937cb23)

### Cart
![Cart](https://github.com/user-attachments/assets/0a1fc1f6-220f-4a9d-b56c-40d5b465a44c)

### Checkout
![Checkout](https://github.com/user-attachments/assets/311794d1-489d-4e01-97f7-f07946efe419)

### User Profile
![Profile](https://github.com/user-attachments/assets/1fb85216-694f-4fc8-b1e4-3cbd2b5651c7)


