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


<img width="941" height="445" alt="image" src="https://github.com/user-attachments/assets/f7afe95f-c2c4-403c-bd56-3f536aabc93b" >

<img width="928" height="446" alt="image" src="https://github.com/user-attachments/assets/81919471-88c7-4092-a319-b7f8813c5489" >
<img width="1856" height="893" alt="Screenshot 2025-09-14 145406" src="https://github.com/user-attachments/assets/50b3569f-81ee-4a97-a176-c2d0484aa147" />

<img width="959" height="438" alt="image" src="https://github.com/user-attachments/assets/80bdbdb4-edee-4fdc-8bfa-01e480782cb9" >

<img width="956" height="416" alt="image" src="https://github.com/user-attachments/assets/3648282b-6d82-4354-89ec-9685592c81f8" >

<img width="945" height="383" alt="image" src="https://github.com/user-attachments/assets/c113d80a-8e65-4410-bae5-5b3d8d9a8409" >

