# 🪙 Gold Price Prediction using Machine Learning

## 📌 Overview

This project aims to predict **gold prices** using historical financial and economic data through a **machine learning regression model**.

The model analyzes relationships between gold prices and various influencing factors such as market indices, oil prices, and currency values to make accurate predictions.

---

## 🚀 Key Features

* Data analysis and visualization using **Pandas & Seaborn**
* Correlation analysis to identify important features
* Feature selection based on relationships with gold price
* Model training using **Random Forest Regressor**
* Evaluation using:

  * R² Score
  * Mean Squared Error (MSE)

---

## 🛠️ Tech Stack

* **Language:** Python

* **Libraries:**

  * NumPy
  * Pandas
  * Matplotlib
  * Seaborn
  * Scikit-learn

* **Tools:**

  * Google Colab
  * Jupyter Notebook

---

## 📂 Dataset

* The dataset contains historical financial data including:

  * Gold price (`GLD`)
  * US Dollar Index (`USO`)
  * Stock indices
  * Oil prices

* Target variable:

  * Gold price (GLD)

---

## ⚙️ Project Workflow

1. Import libraries
2. Load dataset
3. Data preprocessing
4. Exploratory Data Analysis (EDA)
5. Correlation heatmap visualization
6. Feature selection
7. Train-test split
8. Model training using **Random Forest Regressor**
9. Model evaluation using R² score and error metrics

---

## 📊 Model Performance

* The model is evaluated using:

  * **R² Score** (to measure prediction accuracy)
  * **Mean Squared Error (MSE)**

* The Random Forest model provides strong performance due to its ability to capture non-linear relationships in data.


---

## 📈 Sample Prediction

```python id="2k2tcy"
prediction = model.predict(X_test)
print(prediction)
```

---

## ▶️ How to Run

1. Clone the repository:

```bash id="e0y5sv"
git clone https://github.com/Srivarshini04/gold-price-prediction.git
```

2. Install dependencies:

```bash id="t0sd07"
pip install numpy pandas matplotlib seaborn scikit-learn
```

3. Run the notebook:

* Open `.ipynb` file in **Jupyter Notebook** or **Google Colab**

---

## 💡 Future Improvements

* Use advanced models like:

  * XGBoost
  * LSTM (for time-series forecasting)
* Hyperparameter tuning for better accuracy
* Deploy as a web app
* Integrate real-time financial data

---

## 🙋‍♀️ Author

**Srivarshini Komirishetty**

* GitHub: https://github.com/Srivarshini04
* LinkedIn: https://linkedin.com/in/srivarshini-komirishetty

---

## ⭐ Conclusion

This project demonstrates how machine learning can be applied to financial data to predict trends and assist in investment decision-making.

---

## 📜 License

This project is open-source and available under the MIT License.
