# 🔢 Password Strength Analyser
![Last Commit](https://img.shields.io/github/last-commit/reory/password-strength-sim?cacheSeconds=60)
![Repo Size](https://img.shields.io/github/repo-size/reory/password-strength-sim?cacheSeconds=60)
![License](https://img.shields.io/badge/License-MIT-green)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![CustomTkinter](https://img.shields.io/badge/CustomTkinter-1E90FF?style=for-the-badge)

A lightweight, modern, and password analysis tool built with Python, NumPy, and CustomTkinter. This project demonstrates how to use vectorised math to score password security and log audit data in real-time.

---

## 🎯 Why This Project Exists

Weak or reused passwords remain one of the most common causes of security incidents.

This project was created to explore how Python, NumPy, and GUI development can be combined to provide instant password quality feedback through a lightweight desktop application.

The tool demonstrates password scoring techniques, basic security auditing concepts, and user-friendly interface design whilst ensuring that analysed passwords are never stored in log files.

---

## ✨ Key Features

- Real-time password strength analysis
- NumPy-powered scoring engine
- Modern CustomTkinter user interface
- Colour-coded strength indicators
- Password audit logging
- Regex-based complexity checks
- Safe logging without storing passwords
- Lightweight desktop application

---

## Screenshots

![App Screenshot](screenshots/weak.png)
![App Screenshot](screenshots/moderate.png)
![App Screenshot](screenshots/strong.png)

---

## 🛠️ Installation

### Clone the repository:

```Bash
git clone https://github.com/reory/password-strength-sim.git
cd password-strength-sim
```
### Create a virtual environment

```bash
python -m venv venv
```
### Activate the environment

```bash
#Windows
venv\Scripts\activate
```

```bash
# Linux / macOS
source venv/bin/activate
```

### Install dependencies:

```Bash
pip install -r requirements.txt
```

### Run the application:

```Bash
python gui.py
```

---

## 📁 Project Notes

```plaintext
password_strength_sim/
├── screenshots/
│   ├── weak.png
│   ├── moderate.png
│   └── strong.png
├── gui.py
├── password_log.log
└── README.md
```
---

## 🚀 Usage

1. Launch the application.
2. Enter a password in the input field.
3. The scoring engine evaluates:
   - Length
   - Uppercase characters
   - Digits
   - Special characters
4. A strength rating is displayed instantly.
5. Audit activity is logged without storing password values.

---

## 🧠 How It Works (The NumPy Logic)
This project demonstrates how NumPy can be utilised outside traditional data science workflows.

By using vectorised operations such as `np.clip()` and `np.select()`, password metrics can be processed efficiently whilst keeping the scoring logic concise and maintainable.

---

## 👨🏽‍💻 Tech Stack

### Python
- Core application logic.

### NumPy
- Vectorised password scoring and categorisation.

### CustomTkinter
- Modern desktop user interface.

### Regex
- Character pattern detection and validation.

### Logging
- Audit trail generation and diagnostic output.

---

## 🗺️ Roadmap Features

- [ ] Common password blacklist support
- [ ] Shannon entropy-based password analysis
- [ ] Secure password generator
- [ ] Password strength trend visualisation

---

* **Built By Roy Peters** 😁 [![LinkedIn](https://img.shields.io/badge/LinkedIn-Roy%20Peters-blue?logo=linkedin)](https://www.linkedin.com/in/roy-p-74980b382/)