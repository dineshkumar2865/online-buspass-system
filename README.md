# 🚌 Online Bus Pass Renewal Web Application

This is a full-stack web application for applying, renewing, and viewing bus passes online. Built using **HTML**, **CSS**, **JavaScript**, **Flask**, and **SQLite**, it provides users with a smooth and intuitive interface to manage their bus passes easily.

## 🚀 Features

- ✅ User Signup & Login
- 📝 Online Bus Pass Application
- 🔁 Bus Pass Renewal using Pass ID
- 💳 Simulated UPI Payment for Application & Renewal
- 🪪 Bus Pass Display with auto-generated Pass ID and Expiry Date

## 🗂️ Project Structure

buspass system/
├── app.py # Main application file
├── applicant_db.py # Applicant DB logic
├── admin_db.py # Admin DB logic
├── view_register_db.py # View registration info
├── applicant.db # Applicant database
├── admin.db # Admin database
├── register.db # Register database
├── static/
│ ├── css/
│ │ └── style.css # Stylesheet
│ ├── js/
│ │ └── script.js # JavaScript logic
│ └── images/ # Signature & Bus Pass images
├── templates/
│ ├── admin_dashboard.html
│ ├── application.html
│ ├── dashboard.html
│ ├── login.html
│ ├── e_pass.html
│ ├── payment.html
│ ├── submission.html
│ └── table_info.html
└── requirements.txt # Project dependencies

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python (Flask)
- **Database:** SQLite3

## 📸 Pages Overview

1. **Signup/Login** – Secure login and registration with validation
2. **User Home** – Access to application, renewal, and logout
3. **Bus Pass Application** – Form to submit details 
4. **Submission Confirmation** – Message and payment prompt
5. **Simulated UPI Payment** – Manual entry of payment amount
6. **Bus Pass View** – Display with auto-generated ID and expiry
7. **Renewal Form** – Input Pass ID for renewal
8. **Renewed Bus Pass Display** – Updated expiry shown

## ⚠️ Payment Disclaimer

This project uses a **simulated UPI payment system**.

- No real payment processing is involved.
- Users are asked to enter a payment amount manually.
- This is meant **only for testing and demonstration purposes**.

## ▶️ How to Run

1. **Install dependencies**
   pip install -r requirements.txt
2. python app.py
3. http://localhost:5000

## 👨‍💻 Team Members & Roles

- **Dinesh Kumar** – Backend Development & Database Management
- **Mithun** – Frontend Design 
- **Prawin** – Frontend Design 

