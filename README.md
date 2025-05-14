# Laptop_price_predictor
 A machine learning regression project that predicts laptop prices based on hardware specifications using Python and scikit-learn.
# 💻 Laptop Price Predictor (ML Regression Project)

This machine learning project predicts laptop prices based on specifications like brand, processor, RAM, GPU, screen type, etc. It uses regression models to estimate laptop prices accurately using scikit-learn, pandas, and NumPy.

---

## 📊 Dataset

The dataset (`laptop_data.csv`) includes details such as:

- Company
- Type Name
- Screen Size
- Screen Resolution
- Touchscreen
- IPS Panel
- Processor Brand
- RAM (in GB)
- Weight (in kg)
- HDD (in GB)
- SSD (in GB)
- GPU Brand
- Operating System
- Price (Target Variable)

---

## ⚙️ Technologies Used

- Python
- Pandas & NumPy
- Matplotlib & Seaborn (for data viz)
- Scikit-learn (for preprocessing and modeling)
- Google Colab (for implementation)
- GitHub (for version control)

---

## 📈 ML Model

We used a **Random Forest Regressor** wrapped in a **Pipeline** with `ColumnTransformer` and `OneHotEncoder` to handle categorical variables efficiently.

Performance Metrics:
- **R² Score**
- **Mean Absolute Error (MAE)**
