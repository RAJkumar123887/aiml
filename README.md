# 🧠 Smart HR Analytics Dashboard

> AI-powered workforce intelligence platform for employee attrition prediction, sentiment analysis, and natural language HR queries.

![Python](https://img.shields.io/badge/Python-3.11-blue?style=flat-square&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-1.32-red?style=flat-square&logo=streamlit)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.4-orange?style=flat-square&logo=scikit-learn)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## 🚀 Live Demo

👉 **[Launch App on Streamlit Cloud](https://share.streamlit.io)** ← replace with your URL after deploying

---

## ✨ Features

| Module | Description |
|--------|-------------|
| 📊 **Attrition Overview** | Risk charts, salary scatter plots, tenure heatmaps, feature importances |
| 👥 **Employee Risk Table** | Color-coded risk register with CSV export |
| 💬 **Sentiment Analysis** | NLP morale scoring per department with HR alerts |
| 🤖 **AI Query Interface** | Ask HR questions in plain English (GPT + rule-based fallback) |

---

## 🛠 Tech Stack

- **Frontend:** Streamlit, Plotly
- **ML Model:** Random Forest (scikit-learn)
- **NLP:** TextBlob sentiment analysis
- **AI:** LangChain + OpenAI GPT (optional)
- **Data:** Faker (synthetic HR data generation)

---

## ⚡ Quick Start

```bash
# 1. Clone the repo
git clone https://github.com/rajkumar123887/AI-ML-PAYROLL.git
cd AI-ML-PAYROLL

# 2. Install dependencies
pip install -r requirements.txt

# 3. Download TextBlob data
python -m textblob.download_corpora

# 4. Run the app
streamlit run app.py
```

App opens at **http://localhost:8501**

---

## 📁 Project Structure

```
AI-ML-PAYROLL/
├── app.py                  # Main Streamlit dashboard
├── requirements.txt        # Python dependencies
├── utils/
│   ├── __init__.py
│   ├── ai_interface.py     # AI query engine (GPT + rule-based)
│   ├── data_generator.py   # Synthetic HR data generator
│   ├── model.py            # Random Forest training & prediction
│   ├── preprocessing.py    # Feature engineering pipeline
│   └── sentiment.py        # NLP sentiment analysis
├── data/                   # Generated data (runtime)
├── models/                 # Saved models (runtime)
└── assets/                 # Static assets
```

---

## ☁️ Deploy on Streamlit Cloud (Free)

1. Push this repo to GitHub
2. Go to [share.streamlit.io](https://share.streamlit.io)
3. Click **New app** → Select this repo
4. Set **Main file path** to `app.py`
5. Click **Deploy** 🎉

---

## 📸 Screenshots

> Dashboard includes dark-themed interactive charts, employee risk tables, and an AI chat interface.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first.

---

*Built with ❤️ by [rajkumar123887](https://github.com/rajkumar123887)*
