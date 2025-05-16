# Atom Hospital Website

## Overview
Atom Hospital is a web-based hospital management system designed to streamline patient management, staff coordination, and administrative tasks. The system provides interfaces for various roles including doctors, nurses, laboratory staff, receptionists, and administrators.

## Features
- **User Authentication**: Secure login system with role-based access control.
- **Admin Panel**: Manage users, add new users, search for users, and manage patients.
- **Patient Management**: Register, search, and archive patient records.
- **Doctor Interface**: View and manage patient records.
- **Nurse Interface**: Search and manage patient records.
- **Laboratory Interface**: View and manage patient records.
- **Receptionist Interface**: Register patients, search for patients, and manage patient records.
- **Doctor Assistant Interface**: Assist doctors in managing patient records.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript, jQuery
- **Backend**: PHP
- **Database**: SQLite
- **Libraries**: Chart.js, SweetAlert2, Font Awesome

## Setup
1. Clone the repository.
2. Ensure you have a web server with PHP and SQLite support.
3. Place the files in your web server directory.
4. Access the website through your web browser.

## Directory Structure
- **admin/**: Contains admin interface files.
- **bridge/**: Contains backend PHP files for API endpoints.
- **database/**: Contains SQLite database files.
- **js/**: Contains JavaScript files for frontend functionality.
- **logo/**: Contains branding assets.
- **medical/**: Contains medical staff interface files.
- **style/**: Contains CSS files for styling.
- **workspace/**: Contains HTML files for various user interfaces.

## Authentication
The system uses a token-based authentication mechanism. Upon successful login, a token is stored in localStorage, which is used to authenticate subsequent requests.

## Database
The system uses SQLite databases for data storage. The main databases are:
- **users.db**: Stores user information.
- **clinic.db**: Stores patient records.
- **laboratory.db**: Stores laboratory records.
- **archive.db**: Stores archived patient records.
- **with.db**: Stores doctor-assistant relationships.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details. 
