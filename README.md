# 🎓 EduManage

EduManage is a lightweight, user-friendly desktop application built with Python and Tkinter  
for managing student records, attendance, and fees. Designed for schools and universities,  
it offers secure role-based access and a clean interface for admins, teachers, and viewers.

---

## 🚀 Features

- 🔐 Role-based login (Admin / Teacher / Viewer)  
- 👨‍🎓 Add, edit, delete student records  
- 📅 Attendance tracking by grade and class  
- 💰 Fee management and reporting  
- 📁 Built-in user guide (`UserGuide.txt`)  
- 🎬 Splash screen with modern progress bar  
- 🔄 Auto-update system via GitHub Pages  
- 🧩 Packaged as a single `.exe` via PyInstaller  
- 🛠️ Installer built with Inno Setup for easy distribution

---

## 💻 Tech Stack

- **Programming:** Python (Tkinter for GUI)  
- **Database:** SQLite (lightweight & local storage)  
- **Packaging:** PyInstaller + Inno Setup  
- **Update System:** GitHub Pages + JSON manifest

---

## 🚀 Installation

### Option 1: Download Installer

1. Visit [Releases](https://github.com/aashishmandal/EduManage/releases)  
2. Download `EduManageSetup.exe`  
3. Run the installer and follow the wizard  
4. Launch EduManage from Start Menu or desktop icon

### Option 2: Run from Source

git clone https://github.com/aashishmandal/EduManage.git
cd EduManage
pip install -r requirements.txt
python main.py

### 🔑 Default Login
Username: admin

Password: admin123

### 📂 Project Structure
## 📂 Project Structure

```text
EduManage/
├── main.py               # App entry point
├── database.py           # DB setup & default admin logic
├── login.py              # Authentication logic
├── splash.py             # Splash screen module
├── edumanage.db          # SQLite database (sample/default)
├── UserGuide.txt         # User manual
├── icon.ico              # App icon

├── modules/              # Core feature modules
│   ├── students.py
│   ├── attendance.py
│   ├── fee.py
│   ├── settings.py
│   └── admin_settings.py

├── utils/                # Utility functions
│   ├── encryption.py     # Password hashing
│   ├── id_manager.py     # ID generation logic
│   ├── role_guard.py     # Access control decorators
│   └── updater.py        # Auto-update system
---

### 🔄 Auto-Update System
EduManage checks for updates on launch using a hosted version.json file. 
If a newer version is available, users are prompted to download and install it.

Update manifest: https://aashishmandal.github.io/edumanage-site/version.json

---

### 📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

### 👤 Contact
Aashish Mandal Founder & Developer, EduManage 
📧 Email: aashishmandalofficial@gmail.com 
📱 WhatsApp: +977 9819697546
