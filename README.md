# 🏢 Employee Management System (EMS)

A simple yet effective employee management system built with Django that helps organizations manage their employee records, departments, and positions.

## ✨ Features

- 🔐 Secure Authentication System
- 👥 Employee Management
  - Add new employees
  - Edit employee details
  - Delete employee records
  - View employee information
- 🏭 Department Management
  - Create departments
  - Update department details
  - Remove departments
- 💼 Position Management
  - Add new positions
  - Modify position details
  - Delete positions
- 📊 Dashboard with Statistics
  - Total employees count
  - Total departments count
  - Total positions count

## 🛠️ Technologies Used

- **Backend:** Python, Django 3.2.5
- **Database:** SQLite
- **Frontend:** HTML, CSS, JavaScript
- **UI Framework:** Bootstrap, Material Design
- **Additional:** jQuery

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- pip (Python package installer)

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/employee-management-system.git
cd employee-management-system
```

2. Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Run migrations
```bash
python manage.py migrate
```

5. Create a superuser
```bash
python manage.py createsuperuser
```

6. Run the development server
```bash
python manage.py runserver
```

7. Visit `http://127.0.0.1:8000` in your browser

## 📝 Project Structure

ems/
├── employee_information/
│ ├── templates/
│ │ └── employee_information/
│ │ ├── home.html
│ │ ├── login.html
│ │ └── ...
│ ├── models.py
│ ├── views.py
│ └── ...
├── static/
│ └── employee_information/
│ ├── assets/
│ └── ...
└── manage.py



## 🔑 Login Credentials

After creating a superuser, you can log in with:
- Username: username
- Password: password

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/9f7e64d9-1761-448d-87ab-f3880fff1129)


## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

Abdul Rehman Nazeer
- GitHub: [@AbdulRehmanNazeer](https://github.com/AbdulRehmanNazeer)

## �� Acknowledgments

- Django Documentation
- Bootstrap
- Material Design

---
⭐ Star this repository if you find it helpful!
