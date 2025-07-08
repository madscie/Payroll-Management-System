# 💼 Payroll Management System

A desktop-based payroll application built with **Python**, **Tkinter**, and **MySQL**, originally developed as a **school assignment** and currently **under active development**.

## 🎓 Project Status

> **Note:** This project was created as part of a school assignment to demonstrate skills in Python GUI development and database integration. It is still a **work in progress**, and I am actively improving it by adding new features, refactoring code, and enhancing the user experience.

## 🌟 Features

### 🔐 Authentication & Access Control
- Secure login system with role-based access
- Two user roles: **Admin** and **Employee**
- Personalized welcome messages for users

### 👨‍💼 Admin Features
- Create and manage user accounts
- Add and update employee information
- Define job positions and salary structures
- Full access to system settings and data

### 👤 Employee Features
- View personal insurance details
- Generate and print monthly payslips
- Access to personal payroll information only

## 🛠️ Technology Stack

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-green.svg)
![MySQL](https://img.shields.io/badge/Database-MySQL-orange.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## 📸 Screenshots

*Screenshots will be added soon. For now, please refer to the demo video below.*

## 🎥 Demo Video

*A demo video is coming soon. Stay tuned!*

## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- MySQL Server
- pip (Python package installer)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/payroll-system.git
   cd payroll-system
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up the database**
   - Create a MySQL database named `payroll_db`
   - Import the schema:
     ```bash
     mysql -u your_username -p payroll_db < database/schema.sql
     ```

4. **Configure the database connection**
   - Edit `config/database.py` with your MySQL credentials:
     ```python
     DB_CONFIG = {
         'host': 'localhost',
         'user': 'your_username',
         'password': 'your_password',
         'database': 'payroll_db'
     }
     ```

5. **Run the application**
   ```bash
   python main.py
   ```

## 📋 Usage

### Admin Login
- Username: `admin`
- Password: `admin123`

*Please change the default credentials after first login.*

### Employee Login
- Use credentials created by the admin

## 🗄️ Database Schema

The application uses a normalized MySQL database with the following tables:

- `users` – Login credentials and roles
- `employees` – Personal and job details
- `positions` – Job titles and salary grades
- `salary_structure` – Salary components
- `insurance` – Insurance plan details
- `payslips` – Generated payslip records

## 🚧 Roadmap / Future Improvements

- [ ] Add password hashing for security
- [ ] Implement payroll calculations and tax deductions
- [ ] Export payslips to PDF or Excel
- [ ] Improve UI/UX with modern design
- [ ] Add data validation and error handling
- [ ] Dockerize the application for easy deployment

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request. Since this is a learning project, I appreciate feedback and suggestions for improvement.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 👤 Author

**Your Name**  
GitHub: [@yourusername](https://github.com/yourusername)  
LinkedIn: [Your Name](https://linkedin.com/in/yourprofile)  
Email: your.email@example.com

## 🙏 Acknowledgments

- Developed as part of a school assignment for [Course Name]
- Thanks to [Instructor Name] for guidance and support
- Icons and badges from [Shields.io](https://shields.io)

