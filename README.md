**🔍 Lost and Found Information System (LFIS)**
A web-based **Lost and Found Information System (LFIS)** developed using **PHP, MySQL, HTML, CSS, JavaScript, and Bootstrap**.
The system streamlines the process of reporting, managing, and recovering lost and found items through an easy-to-use interface for users and administrators.

**📖 Overview**

The Lost and Found Information System is designed to help organizations, educational institutions, 
and workplaces efficiently manage lost and found items. Users can report lost or found belongings, browse available listings, 
and search for items, while administrators can review and manage all reports from a centralized dashboard.

**✨ Features**

User Features
- Report lost items
- Report found items
- Browse all available items
- Search items by keywords
- View item details with images
- Contact information for item owners/reporters

Admin Features
- Secure admin login
- Manage lost item reports
- Manage found item reports
- Update item status
- Delete incorrect or duplicate reports
- Dashboard for monitoring all activities

**🛠️ Tech Stack**

| Technology | Purpose |
|------------|---------|
| PHP | Backend Development |
| MySQL | Database Management |
| HTML5 | Structure |
| CSS3 | Styling |
| JavaScript | Client-side Functionality |
| Bootstrap | Responsive UI |
| XAMPP | Local Development Environment |

**📂 Project Structure**

LFIS/
│
├── admin/          # Admin panel
├── assets/         # CSS, JavaScript, Images
├── classes/        # PHP classes
├── database/       # Database files
├── inc/            # Common includes
├── items/          # Item-related modules
├── pages/          # Website pages
├── uploads/        # Uploaded item images
├── config.php      # Database configuration
├── index.php       # Homepage
└── ...

**🚀 Installation**

1. Clone the Repository
```bash
git clone https://github.com/Sanskar8105/LFIS.git
```

2. Move to XAMPP
Copy the project into:
```
xampp/htdocs/
```

3. Import Database
- Open **phpMyAdmin**
- Create a new database
- Import the SQL file from the project

4. Configure Database
Update the database credentials inside `config.php`.
Example:
```php
$host = "localhost";
$user = "root";
$password = "";
$database = "lfis";
```

5. Run the Project
Start **Apache** and **MySQL** from XAMPP.
Open:
```
http://localhost/LFIS
```

**🎯 Future Enhancements**
- User Registration & Authentication
- Email Notifications
- AI-based Lost Item Matching
- QR Code Integration
- Mobile Responsive Improvements
- Advanced Search Filters
- Report Analytics Dashboard

**📄 License**
This project is intended for educational and learning purposes.

**👨‍💻 Author**
**Sanskar Kumbhare**
- GitHub: https://github.com/Sanskar8105

⭐ Support
If you found this project helpful, consider giving it a ⭐ on GitHub.
