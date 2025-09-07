# 📲 Scanify: A Smart Receipt Scanner & Expense Manager

🎥 **[Demo Video](https://drive.google.com/file/d/1UPdpdwv-02dSAKvXMcrG6ejsncTUs_LF/view?usp=sharing)**

---


## ❓ Problem Statement #40
Build a tool that:
- **Scans and digitizes receipts**  
- **Automatically categorizes expenses**  
- **Generates reports**  

---


## 📌 Overview
**Scanify** is a comprehensive full-stack application designed to help users efficiently manage their finances by **digitizing, categorizing, and analyzing receipts**.  

The platform features:
- Robust **expense tracking**
- An intuitive **budget manager**
- Detailed **financial reports**

All combined to give users complete control over their spending.

---



## ✨ Key Features

- **🧾 Receipt & OCR Processing**  
  Upload receipts and let the system extract data like store name, date, amount, and items using **OCR**.

- **📂 Automated Expense Categorization**  
  Smartly sorts expenses into categories (Food, Travel, Rent, etc.).

- **💰 Budget Management**  
  Set category-wise budgets, track allocations, and receive **real-time overspending alerts**.

- **📊 Interactive Dashboard & Reporting**  
  Visualize spending trends and habits with a dynamic dashboard.  
  Export **PDF financial reports** for record-keeping.

- **📨 Integrated Contact Form**  
  Sends confirmation emails to users and forwards messages to support.

- **📧 Email Integration**  
  Gmail SMTP-based transactional email system.

---

## ⚙️ Tech Stack
- **Frontend:** React+Vite
- **Backend:** Flask (Python), Flask-Mail, Flask-CORS  
- **Database:** MongoDB Atlas  
- **Authentication:** JWT (JSON Web Tokens), Google OAuth  

---

## 🚀 Getting Started

### 🔹 running Setup
```bash
# Navigate to backend folder
cd backend

# Create a virtual environment
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

# Navigate to frontend folder
cd frontend

# Install dependencies
npm install

# Start development server
npm run dev
