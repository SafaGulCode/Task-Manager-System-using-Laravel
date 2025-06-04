# ✅ Task Manager System – Laravel 12

This is a **Task Management System** built using **Laravel 12**. It supports complete **CRUD operations** (Create, Read, Update, Delete) for managing tasks. It also includes **user authentication**, **role-based access (Admin/User)**, and a **Bootstrap-powered UI** for a clean and responsive layout.

---

## 🔧 Features

* ✅ User Registration & Login (Authentication)
* ✅ Admin/User Roles with Access Control
* ✅ Add, Edit, View, and Delete Tasks
* ✅ Assign tasks to specific users
* ✅ Admin Dashboard to manage all tasks
* ✅ User Dashboard to view assigned tasks
* ✅ Bootstrap 5 design for responsive UI
* ✅ MySQL database integration via XAMPP

---

## 📁 Folder Structure

```bash
System_Project/
├── app/
├── database/
│   ├── migrations/
├── public/
├── resources/
│   ├── views/
│   │   ├── auth/
│   │   ├── tasks/
│   │   ├── layouts/
├── routes/
│   ├── web.php
├── .env
└── README.md
```

---

## 🛠️ Setup Instructions

### Step 1: Clone or Create the Laravel Project

If not created already:

```bash
composer create-project laravel/laravel System_Project
cd System_Project
```

### Step 2: Start XAMPP & Create Database

1. Start **Apache** and **MySQL** in XAMPP
2. Open **phpMyAdmin**
3. Create a new database named: `system_project`

---

### Step 3: Configure `.env`

Edit your `.env` file:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=system_project
DB_USERNAME=root
DB_PASSWORD=


### Step 4: Run Migrations

```bash
php artisan migrate
```

> You will see `migrations DONE` if successful.



### Step 5: Start the Server

```bash
php artisan serve
```

Visit `http://127.0.0.1:8000` in your browser.


## ✍️ Usage

* **Register a new user**
* **Admin** can:

  * Create, edit, delete tasks
  * Assign tasks to users
* **User** can:

  * View assigned tasks
  * Update status if allowed

## 🧪 Testing Features

You can test features like:

* Authentication: Register & login
* Role separation (Admin/User)
* Task creation and assignment
* UI responsiveness

## 🎨 Technologies Used

* Laravel 12 (PHP Framework)
* Bootstrap 5 (CSS Framework)
* MySQL (via XAMPP)
* Laravel Breeze/Fortify (optional for auth scaffolding)


## 🤝 Credits

Developed by: **Usman**
Framework: [Laravel](https://laravel.com/)
UI: [Bootstrap](https://getbootstrap.com/)



## 📌 Future Improvements

* Task due dates & reminders
* Email notifications
* File attachments
* Task comments/chat

