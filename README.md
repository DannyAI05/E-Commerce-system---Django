# 🛒 E-Commerce Management System

A simple **E-Commerce Management System** built with **Django** to demonstrate the basics of online store management. The application allows users to manage products, customers, orders, and inventory using Django's built-in features and an SQLite database.

---

## 📌 Features

- User authentication
- Product management
- Customer management
- Order management
- Inventory tracking
- Django Admin dashboard
- SQLite database integration

---

## 🛠️ Technologies Used

- Python
- Django
- SQLite3
- PowerShell (for running the project)

---

## 📁 Project Structure

```
EcommerceManagementSystem/
│
├── core/              # Main Django application
├── Ecommerce/         # Project configuration
│   ├── settings.py    # Project settings
│   ├── urls.py        # URL routing
│   ├── wsgi.py
│   └── asgi.py
│
├── db.sqlite3         # SQLite database
├── manage.py          # Django management utility
└── requirements.txt   # Project dependencies (optional)
```

---

## ⚙️ Important Files

| File | Purpose |
|------|---------|
| **manage.py** | Executes Django management commands such as running the server and migrations. |
| **settings.py** | Contains project configuration, installed apps, templates, and database settings. |
| **db.sqlite3** | SQLite database used to store application data. |
| **core/** | Main application containing models, views, URLs, forms, and business logic. |

---

## ▶️ Running the Project

Open **PowerShell** in the project folder.

### Activate the virtual environment

```powershell
.\venv\Scripts\Activate
```

### Apply migrations

```powershell
python manage.py migrate
```

### Start the development server

```powershell
python manage.py runserver
```

Open your browser and visit:

```
http://127.0.0.1:8000/admin
```
*CAUTION* Program must be running so as to find page on browser.
---

## 🚀 Future Improvements

- Shopping cart functionality
- Product search and filtering
- Online payment integration
- Order tracking
- Customer reviews and ratings
- Wishlist feature
- Email notifications
- Responsive mobile-friendly design
- Sales reports and analytics

---

## 👨‍💻 Author

**Daniela Wakhu**

Developed as a Django learning project to demonstrate the fundamentals of e-commerce management and full-stack web development.
