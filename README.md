# Appointment Booking App

## 📋 Project Overview
This is a Django-based Appointment Booking App that allows users to register and book appointments.

---

## 🚀 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/AppointmentBookingApp.git
cd AppointmentBookingApp/aaf

### 2. Set Up a Virtual Environment
python -m venv aaf_env
source aaf_env/bin/activate  # On Windows: aaf_env\Scripts\activate

### 3. Install Dependencies
pip install -r requirements.txt

### 4. Apply Migrations
python manage.py makemigrations
python manage.py migrate

### 5. Run the Development Server
python manage.py runserver

### 6. Access the App
http://127.0.0.1:8000

🛠️ Technologies Used
Django
SQLite (or your preferred database)
Python 3.x
