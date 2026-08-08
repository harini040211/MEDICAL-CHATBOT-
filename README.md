# 🌿 Wellness Assistant Chatbot

An intelligent multilingual health assistant chatbot built with Streamlit, featuring user authentication, admin dashboard, and comprehensive health guidance.

## ✨ Features

### 🔐 User Features
- **User Authentication** - Secure login and registration system
- **Multilingual Support** - English, Hindi, and Hinglish
- **Health Guidance** - Symptoms, first aid, and wellness tips
- **Chat History** - Track all your health conversations
- **Personal Health Profile** - Store medical information, allergies, and health goals
- **Response Feedback** - Rate chatbot responses with thumbs up/down

### 👨‍💼 Admin Features
- **Comprehensive Dashboard** - Analytics and key metrics with charts
- **User Management** - View and manage all user accounts
- **System Analytics** - Usage patterns, peak hours, and trends
- **Content Management** - Manage knowledge base and responses
- **Database Management** - Cleanup and maintenance tools

### 📊 Analytics & Insights
- Real-time usage statistics
- Interactive charts (Plotly)
- Top health concerns tracking
- Language distribution analysis
- User demographics
- Daily activity trends
- Response satisfaction rates

## 🚀 Quick Start

### Local Installation

1. **Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/wellness-chatbot.git
cd wellness-chatbot
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Run the application**
```bash
streamlit run app.py
```

4. **Access the app**
- Open your browser to `http://localhost:8501`

## 🌐 Deploy to Streamlit Cloud

1. **Push to GitHub**
```bash
git init
git add .
git commit -m "Initial commit - Wellness Chatbot"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/wellness-chatbot.git
git push -u origin main
```

2. **Deploy on Streamlit Cloud**
- Go to [share.streamlit.io](https://share.streamlit.io)
- Sign in with GitHub
- Click "New app"
- Select your repository: `wellness-chatbot`
- Main file: `app.py`
- Click "Deploy"

## 🔑 Admin Credentials

**Email:** `admin@wellness.com`  
**Password:** `admin123`

⚠️ **Important:** Change these credentials in production!

## 📋 Knowledge Base Coverage

### Symptoms
- Headache
- Fever
- Fatigue
- Stress
- Anxiety
- Cold & Cough
- Stomach issues
- Back pain
- Nausea

### First Aid
- Burns (minor and severe)
- Cuts and wounds
- Sprains
- Nosebleeds
- Choking
- Allergic reactions

### Wellness Tips
- Hydration
- Sleep hygiene
- Exercise
- Nutrition
- Mental health

## 🛠️ Tech Stack

- **Frontend:** Streamlit
- **Database:** SQLite
- **Charts:** Plotly
- **Authentication:** Custom hash-based system
- **Language:** Python 3.8+

## 📁 Project Structure

```
wellness-chatbot/
├── app.py                    # Main application file
├── requirements.txt          # Python dependencies
├── README.md                 # This file
├── assets/                   # Images and static files
│   └── wellness_bot_background.png
└── milestone4_wellness_chatbot.db  # SQLite database (auto-created)
```

## 🔒 Security Notes

- Passwords are hashed using SHA-256
- Admin credentials are currently hardcoded (change for production)
- User sessions are managed by Streamlit
- All user data stored locally in SQLite

## 📝 Database Schema

### Tables
- `users` - User accounts and profiles
- `chat_history` - All chat conversations
- `entity_logs` - Extracted health entities
- `response_feedback` - User ratings
- `admin_logs` - Admin activity tracking

## 🎨 Customization

### Change Background Image
Replace `assets/wellness_bot_background.png` with your image

### Update Knowledge Base
Edit the `WELLNESS_KB` dictionary in `app.py`

### Modify Admin Credentials
Update `ADMIN_CREDENTIALS` in `app.py`

## 🐛 Troubleshooting

**Issue:** App won't start
- Ensure Python 3.8+ is installed
- Run `pip install -r requirements.txt`

**Issue:** Database errors
- Delete `milestone4_wellness_chatbot.db` to reset

**Issue:** Background image not showing
- Check `assets/wellness_bot_background.png` exists
- Image is embedded as base64 in CSS

## 📄 License

This project is open source and available for educational purposes.

## 👥 Contributors

- Your Name - Initial work

## 🙏 Acknowledgments

- Medical information sources (add your sources)
- Streamlit community
- Healthcare professionals who reviewed content

## 📞 Support

For issues or questions, please open an issue on GitHub.

---

**⚕️ Medical Disclaimer:** This chatbot provides general wellness information only and is not a substitute for professional medical advice, diagnosis, or treatment. Always consult qualified healthcare providers for medical concerns.
