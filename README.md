📱 QR Code Based Smart Attendance System

A QR Code Based Smart Attendance Management System built using Python, Flask, SQLite, and Excel to automate classroom attendance.

🚀 Features
📷 Unique QR code for every lecture/session
👨‍🏫 Teacher dashboard for creating attendance sessions
📱 Mobile-friendly student attendance form
✅ Student verification
🚫 Duplicate attendance prevention
🔢 Configurable student attendance limit
🔒 Automatic session closing when the limit is reached
🗄️ SQLite database for data storage
📊 Automatic Excel attendance records
📥 Excel download from the teacher dashboard
🛠️ Technologies Used
Python
Flask
HTML5 / CSS3
SQLite
QRCode
OpenPyXL
UUID
Jinja2
🔄 How It Works
Teacher Creates Session
        ↓
Unique QR Code Generated
        ↓
Teacher Displays QR
        ↓
Student Scans QR
        ↓
Student Enters Details
        ↓
Student Verification
        ↓
Duplicate & Limit Check
        ↓
Attendance Recorded
        ↓
SQLite + Excel
        ↓
Teacher Dashboard
📂 Project Structure
QR-Attendance-System/
│
├── app.py
├── database.db
├── requirements.txt
│
├── templates/
│   ├── index.html
│   ├── teacher.html
│   ├── qr.html
│   ├── student.html
│   ├── success.html
│   ├── closed.html
│   └── dashboard.html
│
├── static/
│   ├── style.css
│   └── qr_codes/
│
└── attendance_excel/
⚙️ Installation
pip install -r requirements.txt

Run the application:

python app.py

Then open:

http://127.0.0.1:5000
🎯 Example

If the teacher sets:

Subject: Machine Learning
Lecture: 5
Students: 30

The system allows attendance until:

30 / 30

After reaching the limit, the session automatically becomes CLOSED.

🔮 Future Improvements
Face recognition
GPS/location verification
Teacher and student login
Attendance percentage calculation
Admin dashboard
Cloud database
Daily/weekly/monthly reports
👨‍💻 Project

QR Code Based Smart Attendance Management System

Developed using Python + Flask + SQLite + Excel.

A smart, digital and mobile-friendly solution for classroom attendance.
