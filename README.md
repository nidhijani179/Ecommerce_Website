<img width="1856" height="893" alt="Screenshot 2025-09-14 145406" src="https://github.com/user-attachments/assets/0e645edb-c1b4-4de0-895f-c726e0ca25b7" />
<img width="1881" height="890" alt="Screenshot 2025-09-14 145243" src="https://github.com/user-attachments/assets/e334eab2-929a-4d64-b231-d15bd1a35481" />
<img width="1890" height="766" alt="Screenshot 2025-09-14 145614" src="https://github.com/user-attachments/assets/3a213c89-a25c-43f6-9f14-cd717f8ea748" />
<img width="1913" height="833" alt="Screenshot 2025-09-14 145537" src="https://github.com/user-attachments/assets/46e3609f-3f07-4003-ba28-d01510d836d9" />
<img width="1919" height="876" alt="Screenshot 2025-09-14 145447" src="https://github.com/user-attachments/assets/fcd1f493-4c6f-43e3-84c8-a66b3200b667" />

# 🛒 Ecommerce Web Application  

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







