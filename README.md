# 🌿 PocketPlant: An E-Commerce Platform for Green Thumbs

## ✨ Project Overview

**PocketPlant** is a modern, performance-focused E-Commerce Web Application dedicated to making it easy for users to browse and purchase plants, gardening supplies, and related products online.

Built primarily using **PHP** and the **Hack** language for enhanced stability and performance, the application provides a smooth, reliable shopping experience from browsing to checkout.

## 🚀 Features

Here are some key functionalities included in the PocketPlant application:

- **Product Catalog:** Browse products organized by categories (e.g., Indoor Plants, Succulents, Tools).
- **User Authentication:** Secure registration, login, and profile management for customers.
- **Shopping Cart Management:** Add, remove, and update quantities of items before checkout.
- **Order Processing:** A streamlined checkout flow to finalize purchases.
- **Performance Focus:** Utilization of Hack (a PHP dialect) suggests an architecture optimized for speed and reliability.

## ⚙️ Technology Stack

This project leverages the following core technologies:

| Category     | Technology                            | Purpose                                                                   |
| :----------- | :------------------------------------ | :------------------------------------------------------------------------ |
| **Backend**  | **PHP** (Primary)                     | Server-side logic, routing, and business operations.                      |
| **Backend**  | **Hack** (HHVM)                       | Enhanced PHP performance and type safety for a more reliable application. |
| **Frontend** | **JavaScript**                        | Dynamic content rendering and client-side interactions.                   |
| **Styling**  | **CSS**                               | Custom styling for a beautiful and responsive user interface.             |
| **Database** | _[Insert Database Here, e.g., MySQL]_ | Persistent storage for user data, products, and orders.                   |

---

## 🛠️ Installation and Setup

Follow these steps to get a local copy of PocketPlant up and running on your machine.

### Prerequisites

- **PHP** (and potentially **HHVM** if you are running the Hack components)
- **Composer** (PHP dependency manager)
- A running **Database Server** (e.g., MySQL/MariaDB)

### Steps

1.  **Clone the Repository:**

    ```bash
    git clone https://github.com/pamodmalith/pocketplant.git
    cd pocketplant
    ```

2.  **Install Dependencies:**

    ```bash
    composer install
    ```

3.  **Create and Configure `.env` File:**

    - Create a copy of the example environment file and name it **`.env`**:
      ```bash
      cp .env.example .env
      ```
    - Open the new **`.env`** file and update the **database credentials** (DB_USERNAME, DB_PASSWORD, etc.) to match your local database settings.

4.  **Database Setup:**
    - Connect to your database server (using a tool like **`mysql`** in your terminal or **phpMyAdmin**).
    - **Create the database** named `pocket_plant`:
      ```sql
      CREATE DATABASE pocket_plant;
      ```
    - **Import the schema and data** from the `dump.sql` file located in the root directory:
      ```bash
      mysql -u [your_db_username] -p pocket_plant < dump.sql
      ```
      _(Note: Replace `[your_db_username]` with your actual username. You will be prompted to enter your password.)_
5.  **Run the Application:**
    - change directory to `/src`
    - _Insert command to start the local development server here (e.g., `php -S localhost:8000 -t public`)._
