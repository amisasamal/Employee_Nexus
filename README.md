# Employee Nexus

**Employee Nexus** is a web-based employee management system built with Flask. It allows organizations to manage employee records, authentication, and related operations through a secure and user-friendly interface.

## 🚀 Features

- User Registration & Login
- Role-based Access Control (Admin, Employee)
- Add, Edit, Delete Employee Records
- View Employee Details
- Password Hashing & Session Management
- Modular Flask Architecture for Scalability

## 🛠 Tech Stack

- **Backend:** Python, Flask
- **Frontend:** HTML, CSS, JavaScript
- **Database:** MySQL (via Flask-SQLAlchemy)
- **Authentication:** Flask-Login
- **Other Tools:** Jinja2, WTForms

## 📁 Project Structure

employee_nexus/
│
├── app/
│ ├── init.py # Initialize Flask app
│ ├── config.py # App configurations
│ ├── models/ # Database models
│ ├── routes/ # Route handlers
│ ├── forms/ # WTForms classes
│ ├── templates/ # HTML templates
│ └── static/ # CSS, JS, images
│
├── run.py # Entry point for app
├── requirements.txt # Python dependencies
└── .flaskenv # Environment variables


## ⚙️ Getting Started

### Prerequisites
Make sure you have Python 3 and MySQL installed.

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/amisasamal/employee_nexus.git
   cd employee_nexus

2. Create a virtual environment
   python3 -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate

3. Install dependencies
   pip install -r requirements.txt

4. Configure the database
  i.Create a MySQL database
  ii.Update database URI in config.py

5. Run the app:
flask run


🤝 Contributing
Contributions are welcome! Please fork the repository and open a pull request for any enhancements or bug fixes.

📄 License
This project is open-source and available under the MIT License.



