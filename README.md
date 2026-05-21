# 🎤 Speech AI Predictor  
### Automated Rubric-Based Speech Evaluation System

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Streamlit-WebApp-red?style=for-the-badge&logo=streamlit">
  <img src="https://img.shields.io/badge/NLP-Powered-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Deploy-Render-purple?style=for-the-badge">
</p>

---

## 📌 Overview

**Speech AI Predictor** is an intelligent NLP-powered speech evaluation system that automatically analyzes speech transcripts and generates rubric-based scores.

The project is designed to be:

✅ Lightweight  
✅ Fast  
✅ Fully customizable  
✅ Easily deployable on Render or any cloud platform  

Unlike heavy AI systems, this project uses traditional NLP and machine learning techniques without requiring PyTorch or Transformers.

---

# 🚀 Features

## ✅ Automated Speech Evaluation

The system analyzes:

- Grammar quality
- Keyword relevance
- Vocabulary richness
- Sentiment
- Speech pacing
- Filler words
- Semantic similarity

---

## ✅ Fully Customizable Rubric System

All scoring logic is controlled through:

```bash
Rubric.xlsx
```

You can modify:

- Criterion names
- Weights
- Keywords
- Descriptions
- Word limits

without changing any code.

---

## ✅ NLP-Based Scoring Engine

The application uses:

| Feature | Technique Used |
|---|---|
| Keyword Matching | TF-IDF |
| Semantic Similarity | Cosine Similarity |
| Grammar Analysis | SpellChecker |
| Vocabulary Richness | Type Token Ratio |
| Sentiment Analysis | VaderSentiment |
| Speech Speed | WPM Calculation |

---

## ✅ Detailed Analytics Dashboard

The app displays:

- Final score (0–100)
- Criterion-wise breakdown
- Grammar error count
- Word count
- WPM
- Vocabulary metrics
- Sentiment polarity
- Filler word frequency

---

# 🧠 System Workflow

```text
User Transcript
       ↓
Text Preprocessing
       ↓
NLP Feature Extraction
       ↓
Rubric Evaluation
       ↓
Weighted Score Calculation
       ↓
Final AI-Based Speech Score
```

---

# 📂 Project Structure

```bash
Speech-AI-Predictor/
│
├── app.py                # Main Streamlit application
├── Rubric.xlsx           # Scoring rubric configuration
├── requirements.txt      # Dependencies
├── README.md             # Documentation
└── images/               # Screenshots (optional)
```

---

# ⚙️ Technologies Used

## 🖥️ Frontend

- Streamlit

## 🧠 NLP & ML

- Scikit-learn
- NLTK
- VaderSentiment
- PySpellChecker
- NumPy
- Pandas

---

# 📊 Evaluation Parameters

The AI evaluates speeches using:

| Parameter | Purpose |
|---|---|
| Keyword Coverage | Topic relevance |
| Grammar Accuracy | Language quality |
| Vocabulary Richness | Lexical diversity |
| Filler Words | Speech fluency |
| Sentiment Score | Emotional tone |
| Speech Rate | Delivery effectiveness |
| Semantic Similarity | Contextual relevance |

---

# 🛠️ Installation Guide

## 1️⃣ Clone Repository

```bash
git clone https://github.com/mjha5279/Speech-AI-Predictor.git
cd Speech-AI-Predictor
```

---

## 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 3️⃣ Run Streamlit App

```bash
streamlit run app.py
```

---

# ☁️ Deployment on Render

## 🔹 Step 1 — Push to GitHub

Upload your project to GitHub.

---

## 🔹 Step 2 — Create Render Web Service

Go to:

```text
https://render.com
```

Create:

```text
New Web Service
```

---

## 🔹 Step 3 — Configure Build Settings

### Build Command

```bash
pip install -r requirements.txt
```

### Start Command

```bash
streamlit run app.py --server.port $PORT --server.address 0.0.0.0
```

---

# 📑 Rubric Format

Your Excel file must contain:

## Sheet Name

```text
Rubrics
```

## Required Columns

| Column Name | Description |
|---|---|
| criterion_name | Name of criterion |
| description | Criterion details |
| keywords | Important words |
| min_words | Minimum allowed words |
| max_words | Maximum allowed words |
| weight | Criterion importance |

---

# 📸 Screenshots

## 🔹 Home Interface

```md
![Home](images/home.png)
```

## 🔹 Analysis Dashboard

```md
![Dashboard](images/dashboard.png)
```

---

# 🔥 Why This Project?

✔ No heavy deep learning frameworks  
✔ Fast execution  
✔ Easy deployment  
✔ Dynamic rubric system  
✔ Modular architecture  
✔ Beginner-friendly  

---

# 📈 Future Improvements

- 🎙️ Real-time voice input
- 🧠 Deep learning scoring models
- 📊 Advanced analytics dashboard
- 🌐 Multi-language support
- 📁 PDF report generation
- ☁️ Database integration

---

# 🤝 Contribution

Contributions are welcome.

Fork the repository and submit a pull request.

---

# 📜 License

This project is licensed under the MIT License.

---

