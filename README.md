# 🏠 House Price Prediction using Linear Regression

A simple Machine Learning project that predicts house prices based on **Area** and **Number of Bedrooms** using **Linear Regression**.

---

## 📌 Project Overview

This project demonstrates the basic Machine Learning workflow:

- Creating a dataset using Pandas
- Splitting data into training and testing sets
- Training a Linear Regression model
- Making predictions on new data

---

## 🛠 Technologies Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## 📂 Project Structure

```
House-Price-Prediction/
│── House_Price_Prediction.ipynb
│── README.md
│── requirements.txt
```

---

## 📊 Dataset

| Feature | Description |
|--------|-------------|
| Area | Size of the house (sq. ft.) |
| Bedrooms | Number of bedrooms |
| Price | House price |

Example dataset:

| Area | Bedrooms | Price |
|------|----------|--------|
| 1000 | 2 | 3000000 |
| 1200 | 3 | 4000000 |
| 1500 | 3 | 5000000 |
| 1800 | 4 | 6000000 |
| 2000 | 4 | 7000000 |

---

## 🤖 Model Used

 - Linear Regression algorithm from Scikit-learn is used to learn the relationship between house features and target price.
---

## 🚀 How to Run

```bash
# Clone repository
git clone https://github.com/your-username/House-Price-Prediction.git

# Go to folder
cd House-Price-Prediction

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook
```

---

## 🚀 Prediction Example

After training the model, you can predict house prices like this:

```python
import pandas as pd

# New house data
new_house = pd.DataFrame({
    "Area": [1600],
    "Bedrooms": [3]
})

# Predict price
predicted_price = model.predict(new_house)

print("Predicted Price:", predicted_price[0])
```

---
## 📈 Result

After training, the model predicts house prices based on input features.

Example output:

```text
Predicted Price:  (output varies based on training data and input values)
```
## 📦 Requirements

Install dependencies:

```bash
pip install pandas scikit-learn jupyter
```

---
## 📌 Conclusion

This project demonstrates a basic implementation of Machine Learning using Linear Regression for predicting house prices.

It helps understand:
- Data preprocessing
- Model training
- Prediction workflow

## 👩‍💻 Author

**Sana Fathima**

---

## ⭐ Note

If you like this project, feel free to ⭐ star the repository!
