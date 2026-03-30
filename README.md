🧾 AI-Powered Complaint Management System

A full-stack web application that allows users to submit complaints and interact with an AI assistant for guidance. The system leverages AI to automatically categorize complaints and generate draft responses, while maintaining an admin-controlled approval workflow with email notifications.

🚀 Live Demo

🔗 Frontend: https://wabi-user-management.netlify.app/

🔗 Backend API: (Add your Render/Server link here)

✨ Key Features
🤖 AI Capabilities
AI-powered chatbot for user support and guidance
Automatic complaint categorization
AI-generated draft responses for submitted complaints
👤 User Features
Submit complaints without registration
Track complaint status
Interact with AI assistant
👨‍💼 Admin Features
Secure admin-only access
Review and manage complaints
Edit and approve AI-generated responses
Send final responses via email
Dashboard for monitoring and tracking complaints
📧 Notification System
Email notifications sent after admin approval

Frontend:

React / HTML / Tailwind CSS / JavaScript

Backend:

Node.js
Express.js

Database:

MySQL

Other:

AI API integration
Nodemailer (email service)
Axios
dotenv
CORS
⚙️ Local Setup Instructions
1. Clone the repository
git clone https://github.com/Heydaraa/Complaint-Support.git
cd your-repo-name
2. Backend Setup
cd backend
npm install

Create a .env file in the backend folder:

DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=your_database_name
DB_PORT=3306

PORT=5000
JWT_SECRET=your_secret_key

# AI API (if used)
AI_API_KEY=your_api_key

# Email configuration
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password

Run the backend:

npm start
3. Database Setup (MySQL)
Start MySQL using XAMPP or MySQL Workbench
Create database:
CREATE DATABASE your_database_name;
Import or create required tables based on your schema
4. Frontend Setup
cd ../frontend
npm install
npm run dev
▶️ Running the Application
Start MySQL server
Start backend server
Start frontend application
Open browser:
http://localhost:5173
📌 System Workflow
Users can:
Ask questions via AI chat
Submit complaints
AI system:
Categorizes complaints
Generates draft responses
Admin:
Reviews complaints
Edits/approves responses
Sends final response via email
📄 License

This project is developed for educational and internship purposes.
