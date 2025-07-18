
# 🧠 Smart Resume Analyzer & Job Fit Predictor

An AI-powered web app that analyzes resumes to predict job-role fit with up to **90% accuracy**. By leveraging machine learning techniques (TF-IDF + Logistic Regression), it processes resumes, classifies potential roles, and suggests top **missing skills** to boost employability.

---

## 🚀 Features

- 🎯 **Resume–Job Fit Prediction** using trained ML model
- 📂 Processes **1,000+ resumes** to classify into predefined roles
- 🔍 Highlights **missing skills** needed to improve job alignment
- ⚙️ Real-time analysis via **Flask backend**
- 🧑‍💼 Personalized career feedback and skill recommendations
- 🧾 Frontend interface for smooth resume uploads and output display

---

## 📊 Tech Stack

- **Frontend**: React.js  
- **Backend**: Flask (Python)  
- **ML/DS**: Pandas, NumPy, Scikit-learn  
- **Model**: TF-IDF + Logistic Regression  
- **Others**: HTML/CSS, JavaScript, Resume Parser

---

## 📁 Project Structure

```

smart-resume-analyzer/
├── backend/       # Flask API + ML model
├── frontend/      # React-based UI
├── model/         # Trained Logistic Regression model & TF-IDF vectorizer
├── data/          # Resume samples for training/testing

````

---

## ⚡ How It Works

1. 📤 User uploads resume (PDF/text)
2. 🧠 Backend parses and transforms it using **TF-IDF vectorization**
3. 🔍 Logistic Regression model predicts the **best job fit**
4. 📈 Missing skills compared against job role expectations
5. 📬 User gets a **personalized report** with recommendations

---

## 🧪 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/Brahmagithubrit/Resume-Analyzer

````

### 2. Set up the backend

```bash
cd backend
pip install -r requirements.txt
python app.py
```

### 3. Set up the frontend

```bash
cd ../frontend
npm install
npm start
```

Visit: [http://localhost:3000](http://localhost:3000)

---

## 📌 Use Cases

* 🚀 Students preparing for placements
* 🧠 Job seekers optimizing resumes
* 🧑‍🏫 Career counselors and resume reviewers
* 🧪 ML-based resume screening demos

---

## 🎯 Results

* 📈 Achieved **\~90% prediction accuracy** on resume–job classification
* 💡 Recommended key skills to improve **career readiness**
* ⚙️ Built for **real-time use**, scalable with more data and job roles

---

## 🛠️ Future Improvements

* 🗣️ Add NLP-based job description analysis
* 📬 Export analysis report as PDF
* 🧠 Add LLM-powered feedback (ChatGPT-style guidance)
* 🔐 Add user authentication for saved reports

---

## 📜 License

MIT License

---

## 👨‍💻 Author

Built with 💼 + 💻 by **Brahma**
[LinkedIn](https://www.linkedin.com/in/brahmananda-tosh-770995266/)

---

## 🔗 Live Demo

[🧠 Try the Resume Analyzer](https://your-live-site-link.com)




