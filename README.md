# Student Management System 🎓🗂️✨

A Flask-powered web app designed for managing academic records using persistent JSON storage, customizable fields, and Excel-compatible operations. 📊💾

## Core Features 📌

### Data Handling & Storage 🧮

- 📁 Stores student information in `students_data.json`
- 📝 Basic fields: Name, Course, Roll number, Section, Year and CGPA
- 🔧 Supports dynamic additional fields
- 🗃️ Uses JSON format for data persistence and easy backup

### Web Interface 🌐

- ➕ Add new students with validation
- 📋 View and manage student records
- ✏️ Edit existing student information
- 📤 Import student data from Excel files

### Application Logic 🧠

- ✨ Implemented Features:
  - ➕ Add new students with validation
  - 📝 View all student records
  - 📤 Import data from Excel files
  - ✅ Input validation and error handling
  - 💡 Flash messages for user feedback
  - 🔧 Support for custom additional fields

### Data Validation 🛡️

- ✅ Required field validation
- 🎯 CGPA validation (0-10 range)
- 📎 Excel import validation:
  - File type verification
  - Template format checking
  - Required column validation
  - Data integrity checks

## Setup & Usage ⚙️

### 1. Installation
```bash
# Clone the repository
git clone https://github.com/Ayushkumar418/student-data-manager.git
cd student-data-manager

# Create and activate virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### 2. Running the Application
```bash
python app.py
```
Access the application at [http://127.0.0.1:5000](http://127.0.0.1:5000)

### 3. Excel Import Format
The Excel file should contain these required columns:
- name
- course
- roll
- sec
- year
- cgpa

Additional columns will be imported as custom fields.

## Dependencies 📦

- Flask==3.0.0
- openpyxl==3.1.2

## Contributing 🤝

Feel free to submit issues, fork the repository, and create pull requests for any improvements.

---

Built with Flask and JSON storage, and Excel integration

