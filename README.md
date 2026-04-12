# 🩺 MedBot – AI-Powered Medical Diagnosis Chatbot

MedBot is a multilingual, AI-powered web application that provides preliminary medical diagnosis based on user-input symptoms. It predicts the most probable disease, suggests common medicines, and recommends a suitable diet — all through a simple and interactive interface.

> 🔧 Built with: **Python, Flask, scikit-learn**
> 🌐 Deployed on: **Render**
> 🎙️ Voice Input + 🌍 Multilingual Support

---

## 🚀 Live Demo

🌐 https://medbot-10.onrender.com

---

## 📸 Screenshots

![Home Page](https://github.com/user-attachments/assets/f76b7408-02b0-4027-b2d4-2edc622dfc58)
*Home Interface*

![Diagnosis Output](https://github.com/user-attachments/assets/935e5497-1868-415e-84d3-1873d4e4c129)
*Prediction Result Display*

---

## 🧠 Features

* ✅ Disease prediction using Machine Learning
* ✅ Medicine and diet recommendations
* ✅ Multilingual support (English, Hindi, Punjabi, Tamil, Bengali)
* ✅ Voice input using Web Speech API
* ✅ Clean and responsive UI
* ✅ Real-time user interaction
* ✅ Cloud deployment on Render

---

## 🛠️ Tech Stack

| Layer               | Tools / Libraries              |
| ------------------- | ------------------------------ |
| **Backend**         | Flask, Python                  |
| **ML/NLP**          | Naive Bayes, TF-IDF Vectorizer |
| **Data Handling**   | Pandas, NumPy                  |
| **Frontend**        | HTML, CSS, JavaScript          |
| **Voice Input**     | Web Speech API                 |
| **Translation**     | deep-translator                |
| **Deployment**      | Render (Gunicorn)              |
| **Version Control** | Git & GitHub                   |

---

## 📂 Project Structure

```
MedBot/
│── app.py
│── preprocess.py
│── templates/
│   └── index.html
│── static/
│   ├── styles.css
│   └── images/
│── models/
│   ├── model.pkl
│   ├── vectorizer.pkl
│   └── disease_info.pkl
│── requirements.txt
│── Procfile
│── render.yaml
│── README.md
```

---

## ⚙️ Installation & Setup

```bash
git clone https://github.com/your-username/Medbot.git
cd Medbot
pip install -r requirements.txt
python app.py
```

Open browser:

```
http://127.0.0.1:5000/
```

---

## 🧪 Model Details

* **Algorithm:** Multinomial Naive Bayes
* **Feature Extraction:** TF-IDF Vectorizer
* **Accuracy:** ~90%
* Evaluated using `classification_report()`

---

## 🎯 Future Enhancements

* 🔹 Deep Learning model integration (LSTM/Transformer)
* 🔹 Doctor consultation API integration
* 🔹 Mobile app version
* 🔹 Improved UI/UX

---

## 👩‍💻 Author

**Ankita Madaan**
🎓 MCA Student | Data Analytics & Machine Learning

---

## ⚠️ Disclaimer

This application is for educational purposes only and should not be considered a substitute for professional medical advice.

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
