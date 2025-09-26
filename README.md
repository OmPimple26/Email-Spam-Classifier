# Email-Spam-Classifier

📧✨ The Email Spam Classifier is a Flask-based 🌐 web app that leverages 🧠 machine learning to analyze email text and classify it as Spam 🚫 or Not Spam ✅. With an interactive web interface, it demonstrates how ML can be applied in real-world email filtering to improve communication safety and efficiency.

[![Python](https://img.shields.io/badge/Python-3.10-blue)](https://www.python.org/)  
[![Flask](https://img.shields.io/badge/Flask-Framework-black)](https://flask.palletsprojects.com/)  
[![Scikit-Learn](https://img.shields.io/badge/ML-ScikitLearn-orange)](https://scikit-learn.org/)  
[![Deployment](https://img.shields.io/badge/Deployed%20on-Railway-6A5ACD)](https://railway.app/)  
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 🔗 Live Demo

My project is deployed and live at:

[https://emailspamclassifier.up.railway.app](https://emailspamclassifier.up.railway.app)  
You can send `POST` requests to `/predict` (expects JSON) to get a spam prediction.

---

## 🛠️ Features & Functionality

- Input email text or features → returns a spam / not-spam prediction  
- RESTful API via Flask  
- Trained ML model (e.g. using scikit-learn) loaded server-side  
- Lightweight, minimal UI (optional)  
- Easy to deploy, test, and extend

---

## Tech Stack / Built With

- 🐍 Python 3.10  
- 🌐 Flask (Backend Framework)  
- 🤖 Scikit-learn (ML Model)  
- 📊 Numpy & Pandas (Data Processing)  
- 🚀 Railway (Deployment Platform) 

---

## 📁 Project Structure 

├── templates/                # HTML templates for Flask
├── LICENSE                   # License file
├── Procfile                  # Start command for deployment (Railway)
├── README.md                 # Project description & instructions
├── main.py                   # Flask app entry
├── manual_spam_detection.py  # Script for manual spam detection/testing
├── model.py                  # Script to train or manage the ML model
├── requirements.txt          # Python dependencies
├── spam.csv                  # Original dataset
├── spam_cleaned.csv          # Preprocessed/cleaned dataset
├── spam_model.pkl            # Trained ML model file
└── vectorizer.pkl            # Text vectorizer for feature extraction

---

## 🚀 Run Locally  

Clone the repo:
```bash
https://github.com/OmPimple26/Email-Spam-Classifier.git
cd Email-Spam-Classifier
```

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

---

## 👨‍💻 Author

Om Pimple

GitHub: https://github.com/OmPimple26

LinkedIn: https://www.linkedin.com/in/om-pimple-0042822b3/

---

## 📜 License

This project is licensed under the MIT License.
