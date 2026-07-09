# 🏠 House Price Prediction using Linear Regression

A Machine Learning project that predicts house prices based on features such as **Square Footage**, **Number of Bedrooms**, and **Number of Bathrooms** using the **Linear Regression** algorithm from Scikit-Learn.

---

## 📌 Project Overview

This project demonstrates the implementation of a **Linear Regression** model for predicting house prices. A synthetic dataset is generated using NumPy and then used to train and evaluate the model.

The project covers the complete Machine Learning workflow:

- Dataset Generation
- Data Preprocessing
- Train-Test Split
- Model Training
- Prediction
- Model Evaluation
- Predicting Prices for New Houses

---

## 🚀 Features

- Generates a synthetic house price dataset
- Uses Scikit-Learn Linear Regression
- Evaluates model using:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score
- Predicts prices for unseen houses
- Displays Actual vs Predicted prices

---

## 📂 Project Structure

```
House-Price-Prediction/
│
├── house_price_prediction.py
├── house_prices_dataset.csv
├── README.md
└── requirements.txt
```

---

## 📊 Dataset

The dataset contains the following features:

| Feature | Description |
|---------|-------------|
| SquareFootage | Area of the house (sq.ft.) |
| Bedrooms | Number of bedrooms |
| Bathrooms | Number of bathrooms |
| Price | Target variable (House Price) |

The dataset is generated automatically using NumPy.

Example:

| SquareFootage | Bedrooms | Bathrooms | Price |
|--------------|----------|-----------|--------|
| 1660 | 2 | 1 | 231455 |
| 2094 | 2 | 3 | 290978 |
| 1930 | 4 | 2 | 293739 |

---

## 🛠 Technologies Used

- Python 3.x
- NumPy
- Pandas
- Scikit-Learn

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/House-Price-Prediction.git
```

Move into the project folder:

```bash
cd House-Price-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python house_price_prediction.py
```

---

## 📈 Model Evaluation

The model is evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

Typical Output:

```
Mean Squared Error : 116010738.06
Root Mean Squared Error : 10770.27
R² Score : 0.9745
```

---

## 🏡 Sample Prediction

Input:

```
Square Footage : 2000
Bedrooms       : 3
Bathrooms      : 2
```

Predicted Price:

```
$294,000 (Approx.)
```

---

## 📚 Machine Learning Workflow

```
Generate Dataset
        │
        ▼
Load Dataset
        │
        ▼
Split Training & Testing Data
        │
        ▼
Train Linear Regression Model
        │
        ▼
Predict House Prices
        │
        ▼
Evaluate Performance
        │
        ▼
Predict New House Price
```

---

## 📸 Output

The program displays:

- Generated Dataset
- Model Coefficients
- Intercept
- Evaluation Metrics
- Predicted Price
- Actual vs Predicted Prices

---

## 📌 Future Improvements

- Use real-world datasets (Kaggle)
- Feature Engineering
- Data Visualization
- Multiple Regression Models
- Hyperparameter Tuning
- Cross Validation
- Model Deployment using Flask/Streamlit
- House Price Prediction Web Application

---

## 🤝 Contributing

Contributions are welcome!

Feel free to fork this repository, create a new branch, and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Shikhar Shauryamaan Singh**

B.Tech CSE (AI & ML)

Machine Learning | Data Science | Python | AI Enthusiast

---
⭐ If you found this project helpful, don't forget to star the repository!
