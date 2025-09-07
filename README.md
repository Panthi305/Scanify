# 📲 Scanify: A Smart Receipt Scanner & Expense Manager

## 📌 Overview
**Scanify** is a comprehensive full-stack application designed to help users efficiently manage their finances by digitizing, categorizing, and analyzing receipts.  

The platform features robust expense tracking, an intuitive budget manager, and detailed financial reports — giving users complete control over their spending.

---

## ❓ Problem Statement #40
The goal is to build a tool that **scans and digitizes receipts**, automatically categorizes expenses, and generates reports.

---

## ✨ Key Features
- **🧾 Receipt & OCR Processing**  
  Upload receipts and let the system extract information (store name, date, amount, items) using Optical Character Recognition (OCR).

- **📂 Automated Expense Categorization**  
  Smart categorization of expenses into predefined groups (Food, Travel, Rent, etc.).

- **💰 Budget Management**  
  Set budgets by category, track allocations, and get **real-time overspending alerts**.

- **📊 Interactive Dashboard & Reporting**  
  Visualize spending trends, track habits, and export detailed reports in **PDF format**.

- **📨 Integrated Contact Form**  
  Built-in contact form that sends confirmation emails to users and forwards messages to support.

- **📧 Email Integration**  
  Gmail SMTP-based transactional email system.

---

## ⚙️ Tech Stack
- **Frontend:** React.js  
- **Backend:** Flask (Python), Flask-Mail, Flask-CORS  
- **Database:** MongoDB Atlas  
- **Authentication:** JWT (JSON Web Tokens), Google OAuth  

---

## 🚀 Getting Started

### 🔹 run  Setup
```bash
## Navigate to backend folder
cd backend

# Create virtual environment
python -m venv venv

# Activate environment
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run application
python app.py


## Navigate to frontend folder
cd frontend

# Install dependencies
npm install

# Start development server
npm run dev
