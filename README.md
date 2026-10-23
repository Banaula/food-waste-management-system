# Food Waste Management System

A food donation and redistribution web application designed to reduce food waste by connecting donors, receivers, admins, and delivery personnel in one platform.

This project is built and maintained by Banaula and is intended for managing leftover food donations efficiently and responsibly.

## Overview

The system helps restaurants, hotels, marriage halls, and general donors donate surplus food instead of wasting it. The platform allows admin staff and delivery teams to coordinate pickup, distribution, and tracking so that food reaches people in need quickly and safely.

## Features

- Donor registration and food donation requests
- Admin approval and management
- Delivery personnel assignment
- Food distribution tracking
- Secure login for users and admins
- Responsive layout for mobile and desktop
- Chatbot support for basic assistance

## Tech Stack

- Frontend: HTML, CSS, JavaScript
- Backend: PHP
- Database: MySQL
- Server: XAMPP / Apache / MySQL stack

## Modules

### User Module
Users can donate excess or leftover food and manage their donation requests.

### Admin Module
Admins can monitor donations, verify users, assign delivery tasks, and manage the overall workflow.

### Delivery Module
Delivery personnel can register, receive pickup assignments, and complete deliveries to the needy community.

## Project Structure

- `index.html` — landing page
- `home.html` — main homepage
- `signup.php` / `signin.php` — user authentication
- `admin/` — admin dashboard and related files
- `delivery/` — delivery module
- `database/` — SQL schema and demo data
- `img/` — project images and assets
- `connection.php` — database connection

## Installation and Setup

1. Download or clone the repository.
2. Place the project folder inside your local web server directory:
   - XAMPP: `xampp/htdocs/`
   - WAMP: `wamp/www/`
   - LAMP: `/var/www/html/`
3. Start Apache and MySQL.
4. Open PHPMyAdmin at `http://localhost/phpmyadmin`.
5. Create a new database.
6. Import the SQL file from the `database` folder.
7. Open the app in your browser:
   - `http://localhost/your-folder-name`

## Run the Project

After setup, start the application from your local server and access the homepage through the browser.

## Demo

Static preview landing page:

https://banaula.github.io/food-waste-management-system/

This is the repo’s own GitHub Pages preview for the front-end landing page. The full PHP/MySQL application still needs to run on a PHP-enabled server environment for complete functionality.

## License

This project is licensed under the MIT License.

## Author

Banaula

## Contact

For questions or collaboration, feel free to reach out through the GitHub profile associated with this repository.
