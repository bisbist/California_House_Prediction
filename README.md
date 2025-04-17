# 🏠 California Housing Price Prediction

This is a complete end-to-end machine learning project that:

- Trains a regression model on the California Housing dataset.
- Serves predictions via a Flask web application.
- Provides a web-based interface for real-time predictions.

---

## 🔧 Project Features

- 🔍 Data Preprocessing using `StandardScaler`
- 🤖 Model Training with `LinearRegression`
- 🌐 Flask API for model inference
- 🎨 User-friendly HTML/CSS frontend
- 📦 Conda-based environment for reproducibility

---

## 📦 Software and Tools Requirements

| Tool / Library       | Description                                         |
|----------------------|-----------------------------------------------------|
| [Python 3.9](https://www.python.org/downloads/release/python-390/) | Core programming language |
| [Conda](https://docs.conda.io/projects/conda/en/latest/index.html) | Environment & dependency manager |
| [scikit-learn](https://scikit-learn.org/stable/) | ML algorithms and preprocessing |
| [pandas](https://pandas.pydata.org/) | Data manipulation and analysis |
| [numpy](https://numpy.org/) | Numerical computations |
| [matplotlib](https://matplotlib.org/) | Data visualization |
| [Flask](https://flask.palletsprojects.com/) | Web framework to serve model |
| [VS Code](https://code.visualstudio.com/) | Code editor |
| [Git CLI](https://git-scm.com/) | Version control |
| [GitHub](https://github.com/) | Code hosting platform |
| [HTML/CSS](https://developer.mozilla.org/en-US/docs/Web/HTML) | Frontend design |

---

## ⚙️ Setup Instructions

### ✅ Step 1: Clone the Repository

```bash
git clone https://github.com/bisbist/California_House_Prediction.git
cd California_House_Prediction
```

### ✅ Step 2 Create and Activate a Virtual Environment

```bash
conda create -p venv python=3.9 -y
conda activate ./venv
```

### ✅ Step 3 Install Dependencies

```bash
pip install -r requirements.txt
```

### ✅ Step 4: Launch the Web Application
```bash
python app.py
```

### 📊 Model Overview

- Dataset: California Housing Dataset (sklearn.datasets.fetch_california_housing)
- Target: Median house value
- Algorithm: Linear Regression (can be swapped with other regressors)
- Metrics: Mean Squared Error, R² Score

--- 

### 🚀 Future Improvements

- Dockerize the application for cross-platform deployment.
- Enable deployment on Heroku or Render.
- Add input validation and exception handling.
