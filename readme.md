# Hotel Management System

## Overview
This project is a Hotel Management System developed using PHP and MySQL. It provides a user-friendly interface for managing hotel bookings, customer details, and room availability.

## Prerequisites

Before you begin, ensure you have the following installed:

- [XAMPP](https://www.apachefriends.org/index.html) (or any other local server that supports PHP and MySQL)

## Installation Instructions
### Installation Instructions

To set up the project, follow these steps:

### Step 1: Install XAMPP

1. Download and install XAMPP from the [official website](https://www.apachefriends.org/index.html).
2. During the installation, ensure that the Apache and MySQL components are selected.

### Step 2: Set Up the Project

1. **Clone the repository or download the project files**:
   - If using Git, run:
     ```bash
     https://github.com/HariMalam/Hotel-Management.git
     ```
   - Alternatively, download the ZIP file and extract it.

2. **Copy files to the htdocs directory**:
   - Locate your XAMPP installation directory (usually `C:\xampp` on Windows).
   - Navigate to the `htdocs` folder (`C:\xampp\htdocs`).
   - Copy the entire project folder into `htdocs`. You can rename it to `hotel_management_system` for convenience.

### Step 3: Set Up the Database

1. **Import the database**:
   - Open XAMPP Control Panel and start Apache and MySQL.
   - Open your web browser and go to `http://localhost/phpmyadmin`.
   - Create a new database:
     - Click on "Databases" and create a new database named `bluebirdhotel`.
   - Import the SQL file:
     - Select the `bluebirdhotel` database.
     - Click on the "Import" tab.
     - Choose the `bluebirdhotel.sql` file from your project root directory and click "Go".

### Step 4: Start the Server

1. Open your web browser and go to:
http://localhost/hotel_management_system


### Usage

- You can now navigate through the Hotel Management System to manage bookings, view customer details, and check room availability.

## Credits

This project was created by **Malam Hari**. Special thanks for their contributions and support.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
