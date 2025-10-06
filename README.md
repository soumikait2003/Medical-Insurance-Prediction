# Insurance Charges Prediction App

This project predicts **medical insurance charges** based on personal details such as age, gender, BMI, number of children, smoking habits, and region.  
It uses a **Machine Learning model** trained on the `insurance.csv` dataset and provides a **Flask web app** interface for user input.

---

## 📂 Dataset
The dataset (`insurance.csv`) contains the following columns:

- `age` → Age of the individual  
- `sex` → Gender (`male` / `female`)  
- `bmi` → Body Mass Index  
- `children` → Number of children  
- `smoker` → Smoking status (`yes` / `no`)  
- `region` → Residential region (`northeast`, `northwest`, `southeast`, `southwest`)  
- `charges` → Medical insurance cost (Target variable)

---

## Tech Stack
- Python
- Flask
- Pandas
- NumPy
- Scikit-learn
- HTML/CSS (for the frontend)

---

## Features
✅ Train a regression model on `insurance.csv`  
✅ Flask app takes user input (Age, BMI, Children, Smoker, Region, etc.)  
✅ Predicts expected **insurance charges**  
✅ Simple web UI 
✅ Deployed on render

---

## Installation

Clone the repository:

```bash
git clone https://github.com/soumikait2003/Medical-Insurance-Prediction.git
cd Medical-Insurance-Prediction
```

Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the Flask app:

```bash
python app.py
```

Open your browser and go to:

```
http://127.0.0.1:5000
```

Enter details like Age, BMI, Smoker, etc. → Get predicted charges 🎉  

---

## UI
![App Screenshot](pic.png)
---

## Model Performance
- Algorithm used: `RandomForestRegressor` 
- Evaluation metrics: RMSE, R² Score

---
## Live Link
https://medical-insurance-prediction-i5n4.onrender.com/
