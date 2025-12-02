# 🥗 NutriBites

**Personalized Diet Recommendation App with Budget-Conscious Meal Planning**

A machine learning-based application that provides personalized meal recommendations based on individual health metrics, dietary goals, and budget constraints.

---

## 📋 Project Overview

|               |                                          |
| ------------- | ---------------------------------------- |
| **Duration**  | 5 weeks (December, 2025 - January, 2026) |
| **Framework** | CRISP-DM Methodology                     |
| **Type**      | Educational Capstone Project             |

### 🎯 Objectives

- Calculate personalized daily calorie needs (BMI, BMR, TDEE)
- Recommend budget-friendly meal plans
- Balance nutrition and cost optimization
- Deploy as interactive web application

---

## ✨ Features

- **Health Metrics Calculation**
  - BMI (Body Mass Index)
  - BMR (Basal Metabolic Rate) using Mifflin-St Jeor formula
  - TDEE (Total Daily Energy Expenditure)
- **Personalized Recommendations**
  - ML-powered food suitability prediction
  - Budget-aware meal combinations
  - Goal-based optimization (weight loss, maintenance, gain)
- **Meal Planning**
  - Daily meal breakdown (Breakfast, Lunch, Dinner, Snack)
  - Calorie and price tracking per meal
  - Nutritional balance considerations

---

## 🛠 Tech Stack

| Category            | Technology                              |
| ------------------- | --------------------------------------- |
| **Language**        | Python 3.12.12                          |
| **ML Framework**    | Scikit-learn (Random Forest Classifier) |
| **Web Framework**   | Streamlit                               |
| **Data Processing** | Pandas, NumPy                           |
| **Visualization**   | Matplotlib, Seaborn, Plotly             |
| **Development**     | Visual Studio Code, Google Colab        |
| **Data Sources**    | FatSecret API                           |
| **Deployment**      | Streamlit Cloud                         |
| **Version Control** | Git, GitHub                             |

---

## 📦 Installation

### Prerequisites

- Python 3.12
- Conda (recommended) or pip
- Git

### Setup

#### 1. Clone repository

```
git clone https://github.com/YOUR_USERNAME/nutribites-app.git
cd nutribites-app
```

#### 2. Create environment

```
conda create -n nutribites python=3.12
conda activate nutribites
```

#### 3. Install dependencies

```
pip install -r requirements.txt
```

#### 4. Verify Installation

```
python --version # Should show Python 3.12.x
python -c "import pandas, sklearn; print('Ready!')"
```

---

## 📁 Project Structure

nutribites-app/  
├── data/ # Dataset storage  
├── notebooks/ # Colab notebooks  
├── src/ # Source code modules  
├── models/ # Trained ML models  
├── tests/ # Unit tests  
├── docs/ # Documentation  
├── app.py # Streamlit app  
└── requirements.txt # Python dependencies

---

## 🌿 Git Workflow

### Branches

- **`main`**: Production code (protected, requires PR approval)
- **`dev-afif`, `dev-anisa`, `dev-gina`, `dev-silvia`**: Personal development branches

### Basic Workflow

#### 1. Checkout your branch

```
git checkout dev-[your-name]
```

#### 2. Make changes and commit

```
git add .
git commit -m "Descriptive message"
```

#### 3. Push to GitHub

```
git push origin dev-[your-name]
```

#### 4. Create Pull Request to main (via GitHub web)

---

## 🗓 Weekly Milestones

| Week   | Focus                  | Status         |
| ------ | ---------------------- | -------------- |
| Week 1 | Data Collection & EDA  | 🚧 In Progress |
| Week 2 | Model Training         | ⏳ Pending     |
| Week 3 | Backend Development    | ⏳ Pending     |
| Week 4 | Deployment             | ⏳ Pending     |
| Week 5 | Polish & Documentation | ⏳ Pending     |

---

## 📄 License

Educational project - not for commercial use.  
Data powered by [FatSecret Platform API](https://platform.fatsecret.com/)

---

**Status:** 🚧 Active Development  
**Last Updated:** December 2, 2025
