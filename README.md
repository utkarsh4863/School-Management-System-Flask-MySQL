# 🏫 School Management System — Flask + MySQL

A fully functional School Management System designed using **Flask**, **MySQL**, and a responsive **Admin Dashboard UI**.  
It streamlines management of **Students, Teachers, Classes, Subjects, Attendance & Reports** in a single platform.

---

## ✨ Features

### 🔐 Authentication & Dashboard
- ✔ **Secure Admin Login**
- ✔ **Interactive Dashboard Statistics**

### 🏫 School Operations

| Module    | Functionalities                       |
|-----------|---------------------------------------|
| Students  | Add / Edit / Delete / View            |
| Teachers  | Add / Edit / Delete / View            |
| Classes   | Manage class info, structure          |
| Sections  | Class-wise section management         |
| Subjects  | Assign subjects to classes            |
| Attendance| Daily attendance per student          |
| Reports   | Student performance & attendance      |

### 📂 Templates Included (UI Pages)

| File Name            | Page Description              |
|----------------------|------------------------------|
| login.html           | Admin login page             |
| dashboard.html       | Main Dashboard page          |
| student.html         | Student list                 |
| edit_student.html    | Student update form          |
| teacher.html         | Teacher list                 |
| edit_teacher.html    | Teacher update form          |
| class.html           | Class management page        |
| edit_class.html      | Edit class info              |
| sections.html        | Manage sections              |
| edit_section.html    | Edit section info            |
| subject.html         | Subject management           |
| edit_subject.html    | Update subject               |
| attendance.html      | Attendance marking page      |
| report.html          | Attendance / results reports |
| header.html          | Reusable UI block            |
| left_menus.html      | Reusable UI block            |
| top_menus.html       | Reusable UI block            |

> 🎨 All pages built with **Bootstrap** for responsive design.

---

## 🛠 Technology Stack

| Technology                | Purpose               |
|---------------------------|-----------------------|
| Python (Flask)            | Web backend           |
| MySQL + flask_mysqldb     | Database              |
| HTML, CSS, Bootstrap      | Frontend UI           |
| Jinja2                    | Template rendering    |
| Font & Icons Libraries    | UI Enhancements       |

---

## 🚀 Getting Started

### Step 1: Create Virtual Environment

```bash
python -m venv venv
```

Activate:

- **Windows**:
  ```bash
  venv\Scripts\activate
  ```

### Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 3: Setup Database

1. **Open MySQL Workbench / phpMyAdmin**
2. **Create Database:**
    ```sql
    CREATE DATABASE python_sms;
    ```
3. **Import File:**  
    📂 `python_sms.sql`

### Step 4: Update DB Credentials in `app.py`

```python
app.config['MYSQL_HOST'] = 'localhost'
app.config['MYSQL_USER'] = 'root'
app.config['MYSQL_PASSWORD'] = 'your_password'
app.config['MYSQL_DB'] = 'python_sms'
```

### Step 5: Run App

```bash
python app.py
```

---

## 📌 App Live On

http://127.0.0.1:5000/

---

## 🔑 Default Admin Login

| Username           | Password    |
|--------------------|------------|
| admin@gmail.com    | admin123   |

---

## 📁 Project Structure

```
📦 School-Management-System-Flask
 ┣ 📂 static
 ┣ 📂 templates
 ┃ ┣ attendance.html
 ┃ ┣ class.html
 ┃ ┣ dashboard.html
 ┃ ┣ ... (other HTML pages)
 ┣ 📄 app.py
 ┣ 📄 python_sms.sql
 ┣ 📄 requirements.txt
 ┣ 📄 README.md
```

---

## 📸 Screenshots _(Add Later)_

Add your UI screenshots here:

![Login Page]https://github.com/utkarsh4863/School-Management-System-Flask-MySQL/blob/main/Dashboard%20image.png
![Dashboard](screenshots/dashboard.png)

---

## 🤝 Contributing

Pull requests are welcome!  
⭐ Star this repo to support the project ❤️

---

## 👨‍💻 Developer

- **Utkarsh**
  - 🟣 GitHub: [@utkarsh4863](https://github.com/utkarsh4863)
