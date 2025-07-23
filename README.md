# 🏡 House Price Prediction using Linear Regression

This project uses a supervised machine learning approach to predict median house prices in California based on various features like income, location, room count, and population using the **California Housing Dataset**.

---

## 📌 Project Overview

The goal of this project is to:
- Perform exploratory data analysis and preprocessing.
- Build a Linear Regression model using `scikit-learn`.
- Evaluate the model using key metrics.
- Save and reuse the trained model with `pickle`.

---

## 🔍 Dataset

- **Source:** `sklearn.datasets.fetch_california_housing`
- **Features include:**
  - Median Income
  - House Age
  - Average Rooms and Bedrooms
  - Population
  - Average Occupancy
  - Latitude & Longitude
- **Target:** Median House Value

---

## 🧰 Tools & Technologies

- Python 🐍
- Google Colab
- `scikit-learn`
- `pandas`
- `numpy`
- `seaborn`, `matplotlib` (for visualization)
- `pickle` (for model serialization)

---

## ⚙️ Workflow

1. **Data Loading**  
   Fetched the dataset using `sklearn.datasets`.

2. **Data Preprocessing**  
   - Feature selection  
   - Normalization with `StandardScaler`  
   - Train-test split

3. **Model Training**  
   Applied `LinearRegression` from `sklearn.linear_model`.

4. **Model Evaluation**  
   - R² Score: `0.59`  
   - Mean Squared Error (MSE)  
   - Mean Absolute Error (MAE)  
   - Root Mean Squared Error (RMSE)

5. **Model Serialization**  
   Saved the model as `model.pkl` using `pickle`.

6. **Prediction**  
   Loaded the saved model and predicted on new data.

---

## 📊 Results

- Model shows a decent fit with an R² score of **0.59**
- Residuals plotted to verify normality assumption
- Metrics used to validate accuracy and robustness

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/house-price-prediction.git
   cd house-price-prediction

2. pip install -r requirements.txt
3. Open House Prediction.ipynb in Jupyter or Google Colab.

---

📦 File Structure
├── House Prediction.ipynb

├── model.pkl

├── requirements.txt

├── README.md

└── screenshots/
    ├── training.png
    ├── residuals.png
    └── metrics.png
    
---

📌 Future Improvements
1. Explore more advanced regression models (e.g., Ridge, Lasso, RandomForest)
2. Implement cross-validation and hyperparameter tuning
3. Create a simple web UI using Flask or Streamlit for deployment

---

🙌 Acknowledgements
Dataset from scikit-learn
Tutorials and inspiration from the open-source ML community

---

📫 Contact
Feel free to connect or reach out:
📧 gaganpatel0205@gmail.com
💼 [LinkedIn](https://www.linkedin.com/in/p-gagan)

---

⭐️ If you found this project helpful, consider giving it a star!

Let me know your GitHub username and I’ll personalize the links (like the repo URL and LinkedIn) for you. I can also help generate the `requirements.txt` file or set up a `screenshots/` folder if needed.
