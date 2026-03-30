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

🛠️ Tech Stack
Frontend
React
Tailwind CSS
JavaScript
Backend
Node.js
Express.js
Database
MySQL
Other Tools & Libraries
AI API Integration
Nodemailer (Email Service)
Axios
dotenv
CORS
⚙️ Local Development Setup
1. Clone Repository
git clone https://github.com/Heydaraa/Complaint-Support.git
cd Complaint-Support
2. Backend Setup
cd backend
npm install

Create a .env file in the backend directory:

DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=your_database_name
DB_PORT=3306

PORT=5000
JWT_SECRET=your_secret_key

# AI API
AI_API_KEY=your_api_key

# Email Configuration
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password

Run the backend server:

npm start
3. Database Setup (MySQL)
Start MySQL (via XAMPP or MySQL Workbench)
Create a database:
CREATE DATABASE your_database_name;
Import or create tables based on your schema
4. Frontend Setup
cd ../frontend
npm install
npm run dev
▶️ Running the Application
Start MySQL server
Start backend server
Start frontend development server
Open your browser:
👉 http://localhost:5173
🔄 System Workflow
User
Interacts with AI chatbot
Submits complaints
AI System
Categorizes complaints
Generates draft responses
Admin
Reviews complaints
Edits and approves responses
Sends final response via email
📁 Project Structure
Complaint-Support/
│── frontend/     # React client
│── backend/      # Node.js + Express API
📌 Notes
Ensure environment variables are properly configured
Email service requires valid credentials
AI features depend on API availability
📄 License

This project is developed for educational and internship purposes.
