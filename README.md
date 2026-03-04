# Django eCommerce Website

A full-featured eCommerce web application built with Django, following the Codemy.com tutorial. This project demonstrates core eCommerce functionality including product listings, shopping cart management, user authentication, and order processing.

---

## 🚀 Features

* User registration and authentication
* Product catalog with categories
* Product detail pages
* Shopping cart functionality
* Add / remove items from cart
* Order checkout system
* Admin dashboard for managing products and users
* Responsive design

---

## 🛠 Tech Stack

* **Backend:** Django (Python)
* **Frontend:** HTML, CSS, Bootstrap
* **Database:** SQLite (default)
* **Version Control:** Git & GitHub

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

### 2. Create and activate a virtual environment

Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

Mac/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run migrations

```bash
python manage.py migrate
```

### 5. Create a superuser (for admin access)

```bash
python manage.py createsuperuser
```

### 6. Run the development server

```bash
python manage.py runserver
```

Visit:

```
http://127.0.0.1:8000/
```

Admin panel:

```
http://127.0.0.1:8000/admin/
```

---

## 📂 Project Structure

```
ecommerce/
│
├── store/              # Main app
├── templates/          # HTML templates
├── static/             # CSS, JS, images
├── db.sqlite3          # Database (development)
├── manage.py
└── requirements.txt
```

---

## 🎯 Learning Objectives

This project helped reinforce:

* Django models, views, and templates
* Working with forms
* Session-based cart systems
* Database migrations
* Admin customization
* Basic eCommerce workflow

---

## 🔒 Future Improvements

* Payment gateway integration (Stripe/PayPal)
* Order history for users
* Product reviews
* Inventory management
* Deployment to production (e.g., Heroku, Render, or VPS)
* Switch from SQLite to PostgreSQL

---

## 📄 License

This project is for educational purposes.

---

## 👨‍💻 Author

Built while learning Django through Codemy.com.
