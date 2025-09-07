Scanify: A Smart Receipt Scanner & Expense Manager
📌 Overview
Scanify is a comprehensive full-stack application designed to help users efficiently manage their finances by digitizing, categorizing, and analyzing receipts. The platform features robust expense tracking, an intuitive budget manager, and detailed financial reports, providing users with the tools they need to maintain control over their spending.

✨ Key Features
Receipt & OCR Processing: Users can upload receipts, and the system uses Optical Character Recognition (OCR) to automatically extract critical information such as the store name, date, amount, and individual items.

Automated Expense Categorization: The application intelligently sorts expenses into predefined categories (e.g., Food, Travel, Rent), simplifying financial organization.

Budget Management: Users can set budget allocations by percentage across different categories. The system provides real-time alerts for overspending to help users stay within their financial limits.

Interactive Dashboard & Reporting: A dynamic dashboard provides a visual overview of spending habits. Users can generate and export financial reports in PDF format for easy record-keeping.

Integrated Contact Form: A built-in contact form sends a confirmation email to the user and forwards their message to support, ensuring effective communication.

Email Integration: The application uses Gmail SMTP for sending transactional emails.

⚙️ Tech Stack
Frontend: React.js

Backend: Flask (Python), along with Flask-Mail and Flask-CORS for email handling and cross-origin requests.

Database: MongoDB Atlas

Authentication: JWT (JSON Web Tokens) and Google OAuth

🚀 Getting Started
To run Scanify locally, follow these steps for both the backend and frontend components.

🔹 Backend Setup
        Navigate to the backend directory:
        cd backend
        
        Create a virtual environment:
        python -m venv venv
        
        Activate the virtual environment:
        
        Windows: venv\Scripts\activate
        
        Mac/Linux: source venv/bin/activate
        
        Install the required dependencies:
        pip install -r requirements.txt
        
        Run the application:
        python app.py

🔹 Frontend Setup
        Navigate to the frontend directory:
        cd frontend
        
        Install the project dependencies:
        npm install
        
        Start the development server:
        npm run dev
