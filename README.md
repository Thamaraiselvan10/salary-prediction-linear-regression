# 💼 Salary Prediction using Linear Regression

A machine learning project that uses **Linear Regression** to predict employee salaries based on years of experience.  
Implemented in **Python** with **pandas, numpy, matplotlib, and scikit-learn**.

---

## 📂 Repository Structure
```
├── Salary.xlsx # Dataset containing years of experience & salary
├── linear_regression_model.ipynb # Jupyter Notebook with full ML workflow
├── README.md # Project documentation
```

---

## 📊 Dataset
The dataset (`Salary.xlsx`) contains two columns:

| YearsExperience | Salary  |
|-----------------|---------|
| 1.1             | 39343   |
| 1.3             | 46205   |
| 1.5             | 37731   |

- **YearsExperience** → Independent variable (X)  
- **Salary** → Dependent variable (y)  

---

## 🚀 Workflow
1. **Import Libraries** → pandas, numpy, matplotlib, scikit-learn  
2. **Load Dataset** → Read Excel file into pandas DataFrame  
3. **Preprocessing** → Extract features (X) and labels (y)  
4. **Split Dataset** → Train-test split (80% training, 20% testing)  
5. **Train Model** → Fit Linear Regression model  
6. **Visualize Results** → Regression line vs training/testing data  
7. **Prediction** → Predict salary for any years of experience  

---

## 📈 Example Prediction
After training, you can make predictions like this:

```python
years_of_experience = [[5]]
predicted_salary = my_model.predict(years_of_experience)
print(f"Predicted Salary for 5 years of experience: {float(predicted_salary[0]):.2f}")
```
> [!IMPORTANT]
> Value may differ slightly based on dataset splits.
Output:
```
Predicted Salary for 5 years of experience: 73245.67
```
---
## ⚡ Features

- ✔ Simple and beginner-friendly Machine Learning project
- ✔ Clean Jupyter Notebook with explanations for each step
- ✔ Visual representation of regression results
- ✔ Dynamic user input to predict salary for any years of experience
---
## 🔧 Installation & Usage

Clone this repository:
```
git clone https://github.com/Thamaraiselvan10/salary-prediction-linear-regression.git
cd salary-prediction-linear-regression
```

Install dependencies:
```
pip install pandas numpy matplotlib scikit-learn openpyxl
```

Launch Jupyter Notebook:
```
jupyter notebook linear_regression_model.ipynb
```

> [!NOTE]
> Run all cells to train the model and visualize results.
---
## 📚 Learning Outcomes

- ✔ Understand the basics of Linear  Regression
- ✔ Learn how to split data into training & testing sets
- ✔ Visualize regression lines and predictions
- ✔ Use a trained model for real-world predictions
---
