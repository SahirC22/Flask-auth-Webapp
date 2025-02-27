# Flask Authentication System  

A **secure user authentication system** built using Flask, SQLite, and Bootstrap 5. This project includes **user registration, login, session management, and a dashboard**.  

## 🚀 Features  
- **User Registration:** Create an account with a username, email, and password.  
- **Secure Login:** Passwords are hashed using Werkzeug.  
- **Session Management:** Users stay logged in until they log out.  
- **Responsive UI:** Bootstrap 5 for a modern and mobile-friendly design.  
- **Logout Functionality:** Users can securely log out.  

## 🛠️ Tech Stack  
- **Backend:** Flask (Python)  
- **Database:** SQLite  
- **Frontend:** HTML, CSS, Bootstrap 5  
- **Security:** Password hashing with Werkzeug  

## 📂 Project Structure  
/flask_auth_app
│── app.py                # Main Flask application
│── database.db            # SQLite database
│── /static
│   ├── styles.css         # Custom CSS for styling
│── /templates
│   ├── base.html          # Base template for layout
│   ├── home.html          # Homepage
│   ├── register.html      # Registration page
│   ├── login.html         # Login page
│   ├── dashboard.html     # User dashboard
│── README.md              # Project documentation
│── LICENSE                # License file
│── .gitignore             # Git ignore file

## 🎯 Installation & Setup  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/SahirC22/flask-auth-Webapp.git
   cd flask-auth-Webapp

2. **Create a virtual environment**
   
   #Mac and Linux:
   ```bash
   python -m venv venvsource venv/bin/activate
   ```
   #Windows:
   ```bash
   venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install flask flask_sqlalchemy werkzeug
   ```
4. **Run the application**
   ```bash
   python app.py
   ```
5. **Open in your Browser**
   http://127.0.0.1:5000

🛡️ Security Features
	•	Hashed Passwords: Passwords are stored securely using Werkzeug hashing.
	•	Session-Based Authentication: Only logged-in users can access the dashboard.
	•	Form Validation: Prevents SQL Injection and XSS attacks.

🌟 Future Enhancements
	•	Google OAuth Login
	•	Email Verification
	•	Profile Page for Users
	•	Two-Factor Authentication (2FA)

   This project is licensed under the MIT License.

🤝 Contributing

Feel free to fork this project and make improvements! Open a pull request if you add any features.

📞 Contact

For any queries, reach out to:
✉️ Email: rajsahir001@gmail.com
🔗 GitHub: SahirC22
---

