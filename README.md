
<p align="center">
  <img src="https://github.com/William-Moriarty7/ATOM-Hospital/raw/main/logo/image.png" alt="Atom Hospital Logo" width="200"/>
</p>

<h1 align="center">ATOM Hospital</h1>

<p align="center">
  <b>A Modern Web-based Hospital Management System</b><br>
  Streamline patient management, staff coordination, and daily hospital operations.
</p>

---

## 🚀 Overview

**ATOM Hospital** is a full-featured hospital management system designed for web platforms. It provides secure, role-based interfaces for doctors, nurses, laboratory staff, receptionists, and administrators, making hospital workflows more efficient and transparent.

---

## 📋 Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Authentication & Security](#authentication--security)
- [Database](#database)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

---

## ✨ Features

- **User Authentication:** Secure login with role-based access control.
- **Admin Panel:** Manage users, add/search users, and oversee patients.
- **Patient Management:** Register, search, and archive patient records.
- **Doctor Interface:** View & manage patient data.
- **Nurse Interface:** Search/manage patient records.
- **Laboratory Interface:** Track lab results and patient records.
- **Receptionist Interface:** Register/search patients, manage records.
- **Doctor Assistant:** Support for doctor-patient record management.
- **Analytics:** Visualize data using Chart.js.
- **Modern Alerts & UI:** Uses SweetAlert2, Font Awesome.

---

## 🛠 Technologies Used

- **Frontend:** HTML, CSS, JavaScript, jQuery
- **Backend:** PHP
- **Database:** SQLite
- **Libraries:** Chart.js, SweetAlert2, Font Awesome

---

## 🏁 Getting Started

1. **Clone the Repository**
   ```bash
   git clone https://github.com/William-Moriarty7/ATOM-Hospital.git
   ```
2. **Set Up Your Environment**
   - Use a web server (Apache, Nginx, XAMPP, etc.) with PHP and SQLite support.
   - Place the files in your web server directory (e.g., `htdocs` for XAMPP).
3. **Access the Web App**
   - Open your browser and go to `http://localhost/ATOM-Hospital` (or your chosen path).

---

## 🗂 Project Structure

```
admin/         # Admin interface (HTML, JS, PHP, CSS)
bridge/        # Backend PHP API endpoints
database/      # SQLite database files
js/            # Frontend JavaScript
logo/          # Branding assets (logos, icons)
medical/       # Medical staff interfaces
style/         # CSS styles
workspace/     # HTML files for user interfaces
```

---

## 🔐 Authentication & Security

- **Token-based Authentication:** On successful login, a token is stored in `localStorage` and used for authenticating subsequent requests.
- **Role-based Access:** Each user role (admin, doctor, nurse, etc.) has access only to relevant functionalities.

---

## 🗄 Database

SQLite databases are used for persistent storage:
- `users.db`: User information.
- `clinic.db`: Patient records.
- `laboratory.db`: Lab records.
- `archive.db`: Archived patients.
- `with.db`: Doctor-assistant relationships.

--

## 📄 License

This project is licensed under the
