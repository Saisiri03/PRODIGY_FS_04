# PRODIGY_FS_04

Here’s an updated **README** file for a **Social Media Platform** using PHP:

---

# Social Media Platform

## Project Overview

The **Social Media Platform** is a web-based application that allows users to interact with each other through posts, comments, and real-time notifications. It features user authentication, profile management, messaging, and more.

## Features

- User authentication (Sign up, Login, Logout)
- Create, edit, and delete posts
- Comment on posts
- Like and unlike functionality
- Follow/unfollow users
- Real-time notifications for likes, comments, and follows
- User profile pages with post history
- Search users and posts
- Private messaging
- Responsive design for both desktop and mobile

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Backend:** PHP (Laravel or Core PHP)
- **Database:** MySQL
- **Real-Time:** Pusher (for notifications) or custom solution
- **Version Control:** Git
- **Deployment:** Apache, Nginx (optional)

## Installation

### 1. Clone the repository:
```bash
git clone https://github.com/your-username/social-media-platform.git
```

### 2. Navigate into the project directory:
```bash
cd social-media-platform
```

### 3. Install dependencies:
If using Laravel:
```bash
composer install
```

### 4. Set up the environment variables:
- Create a `.env` file in the root directory and configure the following details:
  ```bash
  DB_CONNECTION=mysql
  DB_HOST=127.0.0.1
  DB_PORT=3306
  DB_DATABASE=social_media_db
  DB_USERNAME=root
  DB_PASSWORD=your_password

  PUSHER_APP_ID=your_pusher_app_id
  PUSHER_APP_KEY=your_pusher_app_key
  PUSHER_APP_SECRET=your_pusher_app_secret
  ```

### 5. Set up the database:
- Import the `social_media_db.sql` file into MySQL:
  ```bash
  mysql -u root -p social_media_db < social_media_db.sql
  ```

### 6. Run database migrations (if using Laravel):
```bash
php artisan migrate
```

### 7. Serve the application locally:
```bash
php artisan serve
```

### 8. Access the platform:
Visit `http://localhost:8000` in your browser.

## Usage

1. Register a new user or log in with an existing account.
2. Create posts, follow other users, and interact with their content through likes and comments.
3. View your notifications and direct message other users.
4. Customize your profile with personal details and profile pictures.

## Contribution

Feel free to fork the repository, create new branches, and submit pull requests for bug fixes or feature enhancements.



