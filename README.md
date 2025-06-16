# Web Application Security Demo — XSS, CSRF & SQL Injection

This project is an interactive, web-based cybersecurity demonstration tool that showcases three of the most common web application vulnerabilities: Cross-Site Scripting (XSS), Cross-Site Request Forgery (CSRF), and SQL Injection (SQLi) — alongside their secure counterparts.

Built using PHP, MySQL, HTML, and CSS and hosted locally via XAMPP, the platform includes a central admin panel that clearly separates vulnerable and protected implementations with red and green styling for intuitive learning.

Each attack simulation demonstrates how malicious actors can exploit security flaws, while the protected versions incorporate best practices such as input sanitization, CSRF token validation, and SQL prepared statements.

The project also includes a basic attack logging mechanism to simulate real-world threat monitoring.

Designed to serve as both a practical lab and educational aid, this tool enables hands-on penetration testing and reinforces secure coding techniques, making it ideal for cybersecurity training and awareness.

---

## Features

- Demonstrations of **XSS**, **CSRF**, and **SQL Injection** vulnerabilities.
- Secure counterparts for each vulnerability using modern best practices.
- Centralized admin panel to view, add, and delete comments and contact messages.
- Color-coded UI for vulnerable (red) vs. secure (green) implementations.
- CSRF protection with cryptographically secure tokens.
- Use of prepared statements to prevent SQL injection.
- Input sanitization to prevent XSS.
- Attack logging for basic threat monitoring.
- Clean, responsive, and user-friendly interface.

---

## Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
2. **Database Setup**
   Create a MySQL database.
   Import or create tables for comments, contacts, and attack logs as per the schema provided in /database/schema.sql (or your own SQL script).
   Update your db.php file with your database credentials.

3. **Run Locally**

   Use XAMPP, MAMP, or another PHP development environment.
   Place the project folder in your server’s root directory (e.g., htdocs for XAMPP).
   Start Apache and MySQL services.
   Access via your browser: http://localhost/your-project-folder/admin.php
   
**Usage**
Admin Panel: Manage comments and contact messages, view attack logs.
Vulnerable vs. Secure Pages: Navigate through pages demonstrating each vulnerability and its mitigations.
Attack Simulations: Interact with CSRF and XSS attack demos.
Learn: Observe how attacks exploit vulnerabilities and how protections prevent them. 

**Security Notes**
This project is for educational purposes only.
Do not deploy this code in production environments without further security hardening.
Always use HTTPS in real deployments.
Add authentication and authorization for admin areas.
Validate and sanitize all inputs rigorously.
Regularly update your PHP and MySQL versions.

**Contribution**
Contributions, bug reports, and suggestions are welcome! Please open issues or pull requests.

**Author**
Created and maintained by Sadiq Iqbal
Contact: sadiqzq@gmail.com


