# 📈 NEPSE ML Predictor

**A Machine Learning Web Application for Predicting UP/DOWN Movements of NEPSE Stocks**

NEPSE ML Predictor is a machine learning-based web application that analyzes historical Nepal Stock Exchange (NEPSE) data and predicts potential stock price movements. It combines data processing, machine learning, and an interactive web interface to help users explore market information and model-generated predictions.

> **Disclaimer:** This project is intended for educational and research purposes only. Predictions are estimates, not guarantees or financial advice.

## 📌 Project Overview

The goal of this project is to explore how historical stock market data and machine learning can be used to classify potential stock movements as **UP** or **DOWN**.

The application provides a web interface where users can browse companies, explore market information, and view prediction results.

## ✨ Key Features

- 📊 **Stock Movement Prediction** — Generate UP/DOWN predictions using a trained machine learning model.
- 🏢 **Company Explorer** — Browse listed companies and access company details.
- 📈 **Market Dashboard** — Explore market summaries and available market data.
- 👤 **User Authentication** — Access the application through the login system.
- 🔎 **Prediction Dashboard** — View stock prediction results.
- 🗂️ **Historical Data Management** — Support market data management through the application.
- 🎨 **Interactive Web Interface** — Navigate a responsive interface built with HTML, CSS, and JavaScript.

## 🛠️ Technology Stack

| Area | Technologies |
|---|---|
| Language | Python |
| Backend | Flask |
| Machine Learning | Scikit-learn, XGBoost |
| Data Processing | Pandas, NumPy |
| Frontend | HTML, CSS, JavaScript |
| Database | MySQL |
| Visualization | Chart.js |
| Version Control | Git, GitHub |

## 🧠 Machine Learning Workflow

1. Collect historical NEPSE stock market data.
2. Clean and preprocess the data.
3. Prepare relevant features for model training.
4. Train a classification model to predict stock movement.
5. Evaluate the model using appropriate classification metrics.
6. Generate predictions from the trained model.
7. Display prediction results through the Flask web application.

## 📊 Model Evaluation

Model performance should be assessed using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

The model's predictive performance should be reported using the actual results from the final evaluation. Because stock movements are difficult to predict, accuracy alone may not fully describe model performance.

## 🚀 Getting Started

### Prerequisites

- Python
- pip
- Git
- MySQL, if required by your local configuration

### 1. Clone the repository

```bash
git clone https://github.com/asmipandey18/NEPSE_ML_Predictor.git
cd NEPSE_ML_Predictor
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it in Git Bash on Windows:

```bash
source .venv/Scripts/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure environment variables

Review `.env.example` and create a local `.env` file containing the configuration required by your application.

Set up the database and credentials according to the project's configuration. Never publish passwords, API keys, or other secrets.

### 5. Start the application

```bash
python run.py
```

Open your browser and visit:

**http://127.0.0.1:5000**

## 📷 Screenshots

Add screenshots of the actual application here to demonstrate the homepage, dashboard, company details, and prediction results.

Example Markdown syntax:

```markdown
![NEPSE ML Predictor Homepage](screenshots/homepage.png)
```

## ⚠️ Limitations

- Historical patterns do not guarantee future stock movements.
- Predictions can be incorrect due to market uncertainty.
- Model performance depends on data quality and feature selection.
- The application should not be used as the sole basis for investment decisions.

## 🔮 Future Improvements

- Improve feature engineering and model evaluation.
- Integrate more frequently updated market data.
- Add detailed prediction-performance visualizations.
- Enhance stock comparison and analysis features.
- Deploy the application to a production environment.

## 👩‍💻 Author

**Asmi Pandey**

GitHub: [@asmipandey18](https://github.com/asmipandey18)

## 📄 Disclaimer

This project is developed for educational and research purposes. It does not guarantee stock market performance and should not be considered financial advice.