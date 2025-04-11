# 📚 Django Bookstore Application

An end-to-end e-commerce bookstore web application built using Django, MySQL, and Bootstrap. It includes essential features like user registration/login, a searchable book catalog, shopping cart functionality, and a full admin dashboard for managing books, users, and orders. Ideal for learning full-stack web development with Django.

## 📸 Screenshots
![image](https://github.com/user-attachments/assets/255eb7cb-0229-47f7-80b8-9612399bfbaf)
![image](https://github.com/user-attachments/assets/a20b6f4e-89ee-4aad-b50b-627fd36178a1)
![image](https://github.com/user-attachments/assets/d31b102c-bf91-4790-9ae1-8e64a16bb078)
![image](https://github.com/user-attachments/assets/95953af9-202e-45ac-899f-8a8e52997d1a)
![image](https://github.com/user-attachments/assets/f3a62d10-1b0a-420e-9f3a-4b2d89a4c3f8)






## ✨ Features

- **User Authentication**: Login, logout, and registration system
- **Book Catalog**: Browse books by category/publication
- **Shopping Cart**: Add/remove items, view cart total
- **Admin Dashboard**: Manage books, publications, and orders
- **Responsive Design**: Works on mobile and desktop

## 🛠️ Technologies Used

- **Backend**: Django 5.2
- **Database**: MySQL
- **Frontend**: Bootstrap 5, HTML5, CSS3
- **Authentication**: Django Auth System
- **Deployment**: (Specify when deployed)

## 🚀 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/premcodeexplorer/bookstore.git
   cd bookstore
   ```
2. Set up virtual environment:
    ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate    # Windows
   ```
3. Install dependencies:
  ```bash
   pip install -r requirements.txt
   ```
4. Configure MySQL:
   ```bash
   CREATE DATABASE bookstore_db;
   CREATE USER 'bookstore_user'@'localhost' IDENTIFIED BY 'yourpassword';
   GRANT ALL PRIVILEGES ON bookstore_db.* TO 'bookstore_user'@'localhost';
   ```
5. Run migrations:
   ```bash
   python manage.py migrate
   ```
6. Create superuser:
    ```bash
   python manage.py createsuperuser
   ```
7. Run development server:
   ```bash
   python manage.py runserver
   ```
##📂 Project Structure
bookstore_project/
├── bookstore/               # Main app
│   ├── migrations/          # Database migrations
│   ├── static/              # CSS, JS, images
│   ├── templates/           # HTML templates
│   ├── admin.py             # Admin config
│   ├── models.py            # Database models
│   └── views.py             # Application logic
├── bookstore_project/       # Project config
└── manage.py                # Django CLI


