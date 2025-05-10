# Password Strength Checker

A modern web application that evaluates password strength based on various criteria and provides real-time feedback to users. Built with Python (Flask) for the backend and HTML/CSS/JavaScript for the frontend.

---

## 🚀 Features
- **Real-time password strength evaluation**
- **Visual strength indicator** (color-coded bar)
- **Detailed feedback and suggestions**
- **Score-based assessment** (0-5 points)
- **Password visibility toggle**
- **Modern and responsive UI**
- **API endpoint** for server-side validation

---

## 🗂️ Project Structure
```
password-complexity-checker/
├── app.py              # Flask backend (API + serves frontend)
├── requirements.txt    # Python dependencies
├── static/            # Static assets
│   ├── style.css      # Styles
│   └── script.js      # Frontend logic
├── templates/         # HTML templates
│   └── index.html     # Main page
├── .venv/            # Virtual environment
└── README.md         # Project documentation
```

---

## 🛠️ Requirements
- Python 3.7+
- pip (Python package manager)
- Flask >= 2.2.5
- Flask-CORS >= 3.0.10

---

## ⚡ Setup Instructions

### 1. **Clone the Repository**
```bash
git clone <repository-url>
cd password-complexity-checker
```

### 2. **Create and Activate Virtual Environment**
```bash
# Create virtual environment
python -m venv .venv

# Activate virtual environment
# On Windows:
.venv\Scripts\activate
# On macOS/Linux:
source .venv/bin/activate
```

### 3. **Install Dependencies**
```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Application

### 1. **Start the Flask Backend**
```bash
python app.py
```
- The server will start at `http://127.0.0.1:5000`

### 2. **Open the Application in Your Browser**
- Go to [http://127.0.0.1:5000](http://127.0.0.1:5000)
- You should see the Password Strength Checker UI

---

## 🔍 Password Evaluation Criteria
The password strength is evaluated based on the following criteria:
- Length (minimum 8 characters)
- Presence of uppercase letters
- Presence of lowercase letters
- Presence of numbers
- Presence of special characters (e.g., !@#$%^&*)

Each criterion contributes 1 point to the total score (maximum 5 points).

**Strength Classification:**
- 0-2: Weak
- 3-4: Medium
- 5: Strong

---

## 🧪 Example Output
```
Password: Password123
Score: 4/5
Strength: Medium
Feedback: Try adding a special character to make it stronger.
```

---

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

## 📄 License
This project is for educational and demonstration purposes.

---

## 🙋‍♂️ Need Help?
If you have any questions or issues, feel free to open an issue in the repository. 
