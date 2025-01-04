# Courier Management System using PHP-MySQL

## Overview
The Courier Management System is a lightweight PHP/MySQL-based application aimed at assisting courier companies or businesses in managing their customers' parcel details. The system maintains a record of all company branches, which can also serve as designated pickup locations for recipients.

This system includes a parcel tracking feature that monitors the movement and status of parcels, with updates such as:
- "Item Accepted by Courier"
- "Collected"
- "Shipped"
- "In-Transit"
- "Arrived At Destination"
- "Out for Delivery"
- "Ready to Pickup"
- "Delivered"
- "Picked-up"
- "Unsuccessful Delivery Attempt"

These status updates provide clear visibility of parcel progress. Users can choose between two delivery options: **"Deliver"** (direct delivery to the recipient's address) or **"Pickup"** (delivery to a branch close to the recipient). Each item in a shipment is assigned a unique tracking or reference number for easy monitoring.

For instance, if a client ships three packages to the same recipient, each package is treated as a separate entry in the system, each with its own tracking number for precise identification and tracking.

---

## Key Features

### Admin Panel
- **Login Page**: Enables admin users to securely access the system.
- **Dashboard**: Displays an overview and summary of system data post-login.
- **Add New Branch**: Allows administrators to register a new branch.
- **Manage Branches**: Lists all registered branches and provides management options.
- **Add Branch Staff**: Lets admins create accounts for branch staff members.
- **Manage Branch Staff**: Displays all staff accounts across branches with management options.

### Admin and Staff Shared Features
- **Add New Parcel**: Provides functionality for recording parcel details, including sender and recipient information.
- **Manage Parcels**: Displays a list of all parcels and their statuses for management.
- **Track Parcels**: Offers a detailed view of parcel movements and updates.
- **Generate Reports**: Produces printable transaction reports filtered by date range and parcel status.

---

## Technology Stack
This project is built using the following technologies:
- **HTML** for structure
- **PHP/MySQL** for backend and database management
- **CSS** for styling
- **JavaScript (jQuery/Ajax)** for interactivity
- **Bootstrap** for responsive design

The source code is designed to be fully functional and easily customizable.

---

## Installation Instructions
1. Download the project and extract the `.zip` file.
2. Install a local web server with PHP support (e.g., XAMPP, WAMP).
3. Open your database management tool and create a new database named `cms_db`.
4. Import the SQL file from the `database` folder included with the source code.
5. Copy the source code to your web server's project directory, e.g., `C:\xampp\htdocs`.
6. Launch the project in your web browser by visiting: `http://localhost/courier-management-system`.

---

## Default Admin Credentials
- **Username**: `admin@admin.com`
- **Password**: `admin123`

---

## Summary
This Courier Management System is a comprehensive solution for managing parcels and tracking their status. It is suitable for small- to medium-sized courier services and can be tailored to meet specific requirements. Feel free to enhance or modify the source code as needed.
