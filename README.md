# SpendWise

SpendWise is an AI-powered receipt analyzer that helps users make smarter financial decisions by providing economic insights and personalized recommendations. The app analyzes receipts, evaluates purchasing decisions, and suggests alternatives to help users save money over time.

![SpendWise Dashboard](https://github.com/user-attachments/assets/spendwise-dashboard.png)

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Flask](https://img.shields.io/badge/Flask-2.0+-green.svg)](https://flask.palletsprojects.com/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.0+-purple.svg)](https://getbootstrap.com/)

---

## 📖 Project Inspiration

In our lives, coming from middle-class households, shopping as a whole can get expensive. We understand the struggle of balancing expenses while trying to make smart financial decisions. This inspired us to create SpendWise—an app that not only helps track spending but also provides actionable insights to save more.

By leveraging AI to analyze receipts and gamifying smart financial choices, SpendWise transforms mundane shopping trips into opportunities for financial growth and learning. To make the experience even more engaging, we introduced a **multiplayer financial game** where users can compete with friends, family, or a broader community. This competitive element encourages smarter spending decisions while making personal finance fun and collaborative.

---

## 📊 Features

- **Smart Receipt Analysis**: Upload receipt images and extract store details, items, and prices using Google's Gemini AI.  
- **Economic Evaluation**: Evaluate purchases against market data, calculate potential savings, and get an "economic score."  
- **Store Recommendations**: Based on location, receive suggestions for nearby stores with better prices for similar items.  
- **Financial Gamification**: Earn experience points and improve financial stats (frugality, awareness, consistency) by making economical choices.  
- **Multiplayer Financial Game**: Challenge friends to spending competitions—track who saves the most and rank on leaderboards.  
- **Achievement System**: Earn badges and level up by consistently making smart financial decisions.  
- **Personalized Insights**: Get tailored financial advice based on your spending patterns and stats.  
- **User Authentication**: Secure account system with email verification.  
- **Financial Dashboard**: Visualize spending habits and track your savings over time.  

---

## 🛠️ Tech Stack

**Languages:**  
- Python (Backend logic)  
- HTML/CSS/JavaScript (Frontend)  
- SQL (Database queries)  

**Frameworks & Libraries:**  
- Flask (Web framework)  
- SQLAlchemy (ORM)  
- Flask-Login (Authentication)  
- Bootstrap (UI framework)  
- Jinja2 (Templating)  

**APIs:**  
- Google Generative AI (Gemini API)  
- OpenStreetMap  
- Overpass  
- OpenFoodFacts  
- ipinfo.io  

**Platforms:**  
- Google Cloud (Gemini API integration)  
- SQLite/PostgreSQL (Database)  

---

## 📥 Installation

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/yourusername/spendwise.git
   cd spendwise
Create a virtual environment:

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Set up environment variables:
Create a .env file with the following variables:

bash
Copy
Edit
SESSION_SECRET=your_secret_key
MAIL_USERNAME=your_email@gmail.com
MAIL_PASSWORD=your_app_password
MAIL_DEFAULT_SENDER=your_email@gmail.com
Initialize the database:

bash
Copy
Edit
flask init-db
Start the application:

bash
Copy
Edit
flask run
🎮 Usage
Create an account and verify your email.

Add your Gemini API key in the API Keys section.

Upload a receipt image to analyze your spending.

View insights and store recommendations to save money.

Compete in multiplayer spending challenges and track progress via the leaderboard.

📂 Project Structure
php
Copy
Edit
spendwise/
├── backend/
│   ├── templates/        # HTML templates
│   ├── static/           # CSS, JS, and images
│   ├── models.py         # Database models
│   ├── app.py            # Main Flask app
│   ├── ocr_service.py    # Receipt text extraction logic
│   └── categorizer.py    # Expense categorization logic
├── requirements.txt      # Python package dependencies
└── README.md             # Project documentation
🧱 How We Built It
We followed an iterative development process, breaking down the system into core modules and enhancing features over time.

Receipt Processing Pipeline: Utilized Google's Gemini AI for accurate text extraction from receipts.

Economic Analysis Engine: Built algorithms to compare spending with market alternatives.

Location-Based Services: Integrated geographic APIs to find better deals at nearby stores.

Responsive UI: Designed a clean, user-friendly interface using Bootstrap for multi-device support.

Authentication & Security: Implemented secure user authentication with email verification.

🚀 What's Next for SpendWise
Mobile App Development: Launch native iOS and Android versions.

ML-Based Price Predictions: Implement machine learning for future price estimation.

Budget Integration: Incorporate budgeting tools for better expense tracking.

Community Features: Allow users to share savings tips and participate in community challenges.

Personalized Financial Coaching: Enhance AI-driven recommendations for deeper insights.

📜 License
This project is licensed under the MIT License – see the LICENSE file for details.

👥 Contributors
Your Name

Contributor Name
