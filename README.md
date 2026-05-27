# QR-Based Inventory Management System (IMS)

A robust Inventory Management System built with **Laravel 12** and **PHP 8.2**, designed to streamline inventory tracking through QR code integration. This application allows businesses to efficiently manage products, categories, locations, and inventory transactions.

## 🚀 Features

- **QR Code Integration**: Generate and utilize QR codes (`endroid/qr-code` & `simplesoftwareio/simple-qrcode`) for quick product lookups and inventory tracking.
- **Product & Category Management**: Easily organize items into categories and maintain detailed product records.
- **Location Tracking**: Manage multi-location inventory and track where items are stored.
- **Inventory Transactions**: Record stock-ins, stock-outs, and stock adjustments efficiently.
- **Comprehensive Reporting**: Generate detailed reports to monitor stock levels and movements.
- **Dashboard Analytics**: Get an overview of key inventory metrics at a glance.
- **Authentication & Profiles**: Secure access with structured user profiles and role management.

## 🛠️ Tech Stack

- **Backend**: Laravel 12 (PHP 8.2)
- **Frontend**: Blade, Tailwind CSS, Vite
- **Database**: MySQL / SQLite (configurable via `.env`)
- **Testing**: PHPUnit, Pest
- **QR Code Generation**: `endroid/qr-code` & `simplesoftwareio/simple-qrcode`

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd QrBasedIMS-main
   ```

2. **Install PHP dependencies:**
   ```bash
   composer install
   ```

3. **Install NPM dependencies:**
   ```bash
   npm install
   npm run build
   ```

4. **Environment Setup:**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

5. **Configure the Environment:**
   Update your `.env` file with your database credentials.

6. **Run Migrations:**
   ```bash
   php artisan migrate
   ```

7. **Start the Application:**
   ```bash
   php artisan serve
   ```
   *In a separate terminal, run `npm run dev` for frontend asset compilation during development.*

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
