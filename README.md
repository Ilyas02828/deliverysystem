# 🚚 Laravel Delivery Management System

A Laravel-powered Delivery Management System to manage and track parcel deliveries, generate shipping labels with QR codes, and keep sender/receiver information organized. Designed for logistics teams and courier businesses who need a seamless delivery workflow.

![Screenshot](https://your-screenshot-url.com) <!-- Optional image link -->

---

## 📦 Key Features

- 📋 Full CRUD for Deliveries
- 🏷️ Printable Labels with Barcode + QR Code
- 🚚 Real-time Delivery Status Tracking
- 📍 Pickup and Drop-off Address Management
- 🧾 Auto Print-Friendly Label Layout
- 🧑‍💼 Sender & Receiver Info Capture
- 💳 Payment Modes + COD Price Display
- 🛡️ Role-Based Access (Spatie Permissions)
- 📱 Fully Responsive UI (Mobile + Tablet Friendly)

---

## ⚙️ Tech Stack

- **Laravel 11** (PHP 8.2+)
- **Blade Templates**
- **Bootstrap 5**
- **MySQL Database**
- **Spatie Laravel Permission**
- **JsBarcode & Laravel QRCode for Labeling**
- **HTML, CSS, JS**

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/deliverysystem.git
cd deliverysystem
````

### 2. Install Dependencies

```bash
composer install
npm install && npm run build
```

### 3. Environment Setup

Copy the `.env` example file and generate your application key:

```bash
cp .env.example .env
php artisan key:generate
```

Update your `.env` with your database credentials:

```
DB_DATABASE=your_db
DB_USERNAME=your_user
DB_PASSWORD=your_pass
```

### 4. Run Migrations and Seeders

```bash
php artisan migrate --seed
```

### 5. Start the Development Server

```bash
php artisan serve
```

Visit: `http://localhost:8000`

---

## 🔒 Roles & Permissions

* **Super Admin** – Full Access
* **Admin** – Manage Deliveries & Users
* **Employee** – View & Print Assigned Deliveries

Manage roles using the `Spatie/laravel-permission` package.

---

## 🖨️ Printing Labels

Each delivery has a **"Print Label"** button which opens a print-ready layout. Only the label section is printed without sidebar or header.

> ✅ Auto-centering
> ✅ Barcode & QR Code included
> ✅ Size optimized for sticky label sheets

---

## 📁 Folder Structure Overview

* `/app/Models/Delivery.php` – Eloquent Model
* `/resources/views/deliveries/` – Blade Views (index, show, label-print)
* `/routes/web.php` – Routes
* `/app/Http/Controllers/DeliveryController.php` – CRUD logic

---

## 🛠 Future Enhancements

* SMS notifications on delivery status
* Real-time delivery tracking map
* API for mobile app integration
* Export labels as PDF

---

## 🧑‍💻 Author

Developed by **\[Your Name]**
🔗 [EngrIlyas.com](https://www.linkedin.com/in/ilyas02828/)
📧 [Ilyas02828@gmail.com](mailto:Ilyas02828@gmail.com)

---

## 📢 Contributing

PRs and issues are welcome! Please fork the repo and submit your improvements.

---

## 🌐 License

This project is open-source under the [MIT License](LICENSE).

---

## 🔗 Hashtags

**#Laravel #PHP #DeliverySystem #PackageTracking #Logistics #OpenSource #ProductivityTool #WebApp #MySQL #AdminPanel #SpatiePermissions #CRUD #BarcodeLabel #QRCode #LaravelDeveloper #PHPDeveloper #BladeTemplates #Bootstrap #PrintFriendly #DevTools #ShippingLabel #CourierSystem**


