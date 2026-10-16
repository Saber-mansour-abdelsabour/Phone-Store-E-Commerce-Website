
# 📱 Phone Store E-Commerce Website

A full-stack e-commerce website for selling mobile phones, built using HTML, CSS, JavaScript, Laravel, and MySQL.

## 📌 About The Project

This project is an online phone store that provides a user-friendly shopping experience for browsing mobile phones and viewing product details.

It also includes an admin dashboard for managing products, categories, and customer orders.

## ✨ Features

### 🛍️ Customer Website
- Responsive user interface.
- Browse and view mobile phone products.
- Product details and images.
- Frontend built with HTML, CSS, and JavaScript.
- Integration with Laravel REST API.

### ⚙️ Admin Dashboard
- Manage products (Create, Read, Update, Delete).
- Manage product categories.
- Manage customer orders.
- Upload and manage product images.
- Authentication and input validation.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| CSS3 | Styling and responsive design |
| JavaScript | Frontend interactions |
| PHP | Backend programming |
| Laravel | REST API and backend logic |
| MySQL | Database management |

## 🏗️ Project Architecture

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Laravel REST API
- **Database:** MySQL
- **Communication:** HTTP requests between the frontend and API

## 🚀 Getting Started

### Prerequisites

Make sure you have installed:

- PHP
- Composer
- MySQL
- Node.js and npm (if required by your Laravel setup)

### Installation

1. Clone the repository:

   ```bash
   git clone YOUR_REPOSITORY_URL
   ```

2. Navigate to the project directory:

   ```bash
   cd phone-store
   ```

3. Install PHP dependencies:

   ```bash
   composer install
   ```

4. Create your environment file:

   ```bash
   cp .env.example .env
   ```

   On Windows, you can copy `.env.example` and rename the copy to `.env`.

5. Generate the application key:

   ```bash
   php artisan key:generate
   ```

6. Configure your database credentials in `.env`:

   ```env
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=phone_store
   DB_USERNAME=root
   DB_PASSWORD=
   ```

7. Run database migrations:

   ```bash
   php artisan migrate
   ```

8. Start the Laravel development server:

   ```bash
   php artisan serve
   ```

Follow the project-specific setup instructions to run the frontend and connect it to the API.

## 🔐 Security

- Authentication for protected operations.
- Server-side request validation.
- Protected configuration using environment variables.

## 📷 Screenshots

Add screenshots of the store and admin dashboard here.

```markdown
![Home Page](screenshots/home-page.png)
![Products Page](screenshots/products-page.png)
![Admin Dashboard](screenshots/admin-dashboard.png)
```

## 👨‍💻 Author

**Your Name**

- GitHub: [Your GitHub Profile](https://github.com/YOUR_USERNAME)
- LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/)

## 📄 License

This project is available for learning and portfolio purposes.
