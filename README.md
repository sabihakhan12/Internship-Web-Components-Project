# Internship-Web-Components-Project
A simple PHP-based Login and Contact Form project built during internship. Includes secure login/logout with dashboard, and a contact form with MySQL integration. Uses HTML, CSS, JS, PHP, and SQL. Fully functional and ready to deploy with database files included.


---

## 🔐 Login System

The login module includes a secure login form, backend authentication, session management, and a dashboard page only accessible to logged-in users.

### ✅ Features:
- PHP login with session handling
- Redirect to dashboard on success
- Logout functionality
- SQL file included (`users.sql`) for setup

---

## 📩 Contact Form

The contact form module lets users submit queries, feedback, or contact info. It stores the data into a MySQL table using PHP backend logic.

### ✅ Features:
- Responsive HTML/CSS form
- JavaScript form validation
- PHP backend to store messages
- SQL file (`edumart.sql`) for DB setup

---

## ⚙️ Technologies Used

- HTML5
- CSS3
- JavaScript
- PHP
- MySQL
- XAMPP (local server)

---

## 🚀 How to Run the Project

### 📌 Prerequisites:
- XAMPP or any local server (Apache + MySQL)
- A code editor like VS Code

### 🧪 Setup Instructions:

1. Place both folders (`log_in/` and `contact/`) into your XAMPP `htdocs/` directory.
2. Open XAMPP Control Panel and start **Apache** and **MySQL**.
3. Go to **phpMyAdmin** and do the following:
   - Create a database (e.g., `login_db`) and import `users.sql`.
   - Create another database (e.g., `contact_db`) and import `edumart.sql`.
4. Edit `login.php` and `contact.php` files to match your DB credentials if needed.
5. Run the pages in your browser:
   - Login: `http://localhost/log_in/late/login.html`
   - Contact: `http://localhost/contact/contact/contact.html`

---

## 🧾 Sample Database Login Credentials

Edit these in your `users.sql` before importing or add manually:

```sql
-- Example row
INSERT INTO users (username, password) VALUES ('admin', '1234');
