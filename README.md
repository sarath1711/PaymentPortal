# 💳 PaymentPortal

**PaymentPortal** is a Django-based web application that enables users to effectively **track financial disbursements, manage payments, generate payment requisitions, and obtain approvals**.  

In addition to core payment management, it integrates **advanced AI-based automation** and **QR code payment functionality** for a modern, user-friendly experience.

---

## 📂 Project Structure
PaymentPortal/
│── db.sqlite3 # SQLite database file
│── manage.py # Django project management script
│
├── registration/ # Handles user authentication and registration
├── static/ # Static files (CSS, JS, images)
├── templates/ # HTML templates for frontend
├── local/ # Local configurations (optional: settings, environment)
├── media/ # Uploaded media files
└── paymentsportal/ # Core project settings and configuration


---

## 🚀 Features

### 🔑 Core Payment Features
- 📊 **Track Financial Disbursements**  
- 🧾 **Generate & Manage Payment Requisitions**  
- ✅ **Approval Workflow for Payments**  

### 💳 Payments Using QR Codes
- 🖨️ **QR Code Generator** → Creates QR codes for **GPay, PhonePe, and UPI** payment information.  
- 📱 **Scan & Pay** → Users complete transactions by simply scanning the QR code.  
- 🔗 **Accepts UPI IDs** (e.g., `sara*************`).  

### 🤖 AI & Automation Features
- ✋ **Hand Gesture Control** → Navigate and authorize payments using gestures.  
- 🎙️ **Voice Command Support** → Perform actions via voice input.  
- 👁️ **Eye-Controlled Mouse** → Navigate the system through **eye-tracking**.  
- 📷 **Computer Vision Integration** → Leverages a webcam for real-time interaction.  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/PaymentPortal.git
cd PaymentPortal
2️⃣ Create a Virtual Environment
bash
Copy code
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows
3️⃣ Install Dependencies
bash
Copy code
pip install -r requirements.txt
4️⃣ Apply Migrations
bash
Copy code
python manage.py makemigrations
python manage.py migrate
5️⃣ Run Development Server
bash
Copy code
python manage.py runserver
👉 Access the app at: http://127.0.0.1:8000/

🛠️ Tech Stack
Backend: Django (Python)

Database: SQLite (default) → can be switched to PostgreSQL/MySQL

Frontend: Django Templates, HTML, CSS, JS

AI & Automation: OpenCV, MediaPipe, SpeechRecognition, Eye Tracking APIs

Payment Gateway: QR-based UPI (GPay, PhonePe, etc.)

👨‍💻 Project Information
This project was developed independently by me.

You might also see this project shared in other places, as I continue to improve and demonstrate it.
