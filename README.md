# 🎓 University Alumni Management System - AlumSphere

![PHP](https://img.shields.io/badge/PHP-7.4%2B-blue)
![MySQL](https://img.shields.io/badge/Database-MySQL-lightgrey)
![License: MIT](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Project-University%20Assignment-blueviolet)

A web-based alumni management platform designed for universities and academic institutions to manage alumni data and organize events. The system includes both an admin panel and user interface with CSV data handling and event participation tracking.

---

## 🚀 Features

### 🔐 Admin End
- View all uploaded alumni
- Add and manage university events
- Track alumni event responses

### 👤 User End
- Log in to the system
- Upload alumni details via CSV file
- View upcoming events
- Confirm participation in events

---
---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS (Vanilla)
- **Backend**: PHP
- **Database**: MySQL (via XAMPP)
- **Tool**: phpMyAdmin for DB management

---

## 📦 Database Tables

This project uses the following MySQL tables:

- `admin` – admin login credentials
- `users` – user/alumni login details
- `alumni` – uploaded alumni data
- `events` – event titles, dates, descriptions
- `event_responses` – stores alumni participation

You can find the table structure in:  
📁 `sql/database_schema`

---

## 📌 How to Set Up (Localhost)

1. **Clone the repository** or download the ZIP
2. Place the folder in `htdocs/` (XAMPP)
3. Start Apache & MySQL via XAMPP Control Panel
4. Import the SQL file from `/sql/database_schema` using phpMyAdmin
5. Update `/dtaabase/db_connect.php` with your MySQL credentials
6. Open `http://localhost/alumni-management-system/index.php`

**important: for the ease i have uploaded the files as folders ,to run the exact code you must copy only the files and paste them in htdocs | or else please update the code with file locations before execution
example:
Old:
```
include 'db_connect.php';
```
New:
```
include '../db/db_connect.php';
```
---

## 🧾 CSV Upload Format

When uploading alumni data via CSV, make sure your file includes these fields in order:


Sample file available at:  
📄 `sample_Data.csv`

---

## 📷 Screenshots
<ul>

  <li>Home</li>

  ![Screenshot 2025-06-28 124435](https://github.com/user-attachments/assets/6d6359c2-d74e-40e7-a580-131abd2fca6a)
  

  
<li>Upload csv </li>

![Screenshot 2025-06-28 075825](https://github.com/user-attachments/assets/b37bf54e-370a-42d2-abec-5f5dea36033f)

<li>Manage Events</li>

![Screenshot 2025-06-27 215712](https://github.com/user-attachments/assets/9aefa397-5c2a-445d-aba4-826c6aba818b)


<li>My Details_User end</li>

![Screenshot 2025-06-27 214224](https://github.com/user-attachments/assets/ea7116a2-0486-4de3-a003-6e935466da18)

<li> Event _User end</li>

![Screenshot 2025-06-27 214251](https://github.com/user-attachments/assets/a180ba5a-f7e7-435b-adc8-2160b3cd6d86)

</ul>


## 🤝 Contributions

This is a university project. Contributions, suggestions, or improvements are welcome via pull requests or issues.

---

## 📃 License

MIT License – You are free to use, modify, and distribute this project.

---

## 🙋‍♀️ Author

**Shalini Wanasinghe**  
University of Vavuniya – Faculty of Applied Sciences  
🗓️ Year: 2025  
📧 Feel free to reach out

---

`PHP`, `MySQL`, `Alumni Management System`, `University Project`, `Web Application`, `CSV Upload`, `Event Management`, `Admin Dashboard`, `Open Source`, `Student Project`, `University System`, `Academic Portal`, `XAMPP`, `phpMyAdmin`, `Database Project`, `User Authentication`, `Alumni Portal`, `Backend Development`, `MIT License`
