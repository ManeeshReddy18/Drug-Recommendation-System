# Drug-Recommendation-System
This Streamlit-based web application enables users to input their symptoms and receive intelligent disease predictions along with personalized medical recommendations. It leverages Google Gemini's generative AI to interpret symptoms and generate treatment advice, which can be downloaded as a PDF.

🔧 Features
🔐 User Registration & Login with secure password hashing

💬 Symptom-based AI Consultation using Gemini Pro API

📄 PDF Report Generation with recommendations

📤 PDF Upload and Text Extraction for staff analysis

🗄️ MySQL Database Integration for user management

🌐 Streamlit Interface for interactive usage

🛠️ Tech Stack
Frontend & UI: Streamlit

Backend: Python

Database: MySQL

AI Integration: Google Gemini API

PDF Handling: ReportLab & PyPDF2

📌 Setup Instructions
Clone the repo

Set up your .env with your Gemini API key

Run the Streamlit app:

bash
Copy
Edit
streamlit run app3.py
Ensure your MySQL database has a users table for authentication.

