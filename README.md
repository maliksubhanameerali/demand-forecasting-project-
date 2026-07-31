# 📈 Demand Forecasting & Prediction System

An end-to-end machine learning project for predicting product demand using **Python, XGBoost, and Scikit-learn**. This project demonstrates the complete machine learning workflow, from data preprocessing and exploratory data analysis (EDA) to feature engineering, model training, evaluation, visualization, model serialization, and deployment through an interactive Streamlit application.

## 📌 Project Overview

Accurate demand forecasting helps businesses optimize inventory, reduce operational costs, minimize stockouts, and make better data-driven decisions.

This project uses historical product demand data and machine learning techniques to predict demand based on relevant product, sales, and business-related features.

The project includes data visualization, data preprocessing, feature engineering, model training, evaluation, model serialization, and deployment of the trained model through an interactive Streamlit prediction application.

## ✨ Features

📊 Exploratory Data Analysis (EDA)
🧹 Data preprocessing and cleaning
⚙️ Feature engineering
🤖 XGBoost regression model
📈 Model evaluation
📉 Data visualization and business insights
🎯 Feature importance analysis
📢 Promotion impact analysis
💾 Saved trained model using Pickle
🔤 Saved label encoders for preprocessing
🖥️ Interactive Streamlit prediction application
🔄 Reusable prediction pipeline

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Streamlit
* Pickle
* Jupyter Notebook
* Google Colab

## 📂 Project Structure

```text
demand-forecasting/
│
├── Demand_Forecasting_Project.ipynb
├── app.py
├── xgb_model.pkl
├── label_encoders.pkl
├── demand_forecasting.csv
├── images/
│   ├── daily_demand.jpeg
│   ├── feature_importance.jpeg
│   ├── promotion_impact.jpeg
│   └── README.md
└── README.md
```

## 📊 Visualizations

### 📈 Daily Demand Over Time

This visualization shows daily demand patterns from **2022 to 2024**, highlighting fluctuations and periods of higher and lower demand.

![Daily Demand Over Time](images/daily_demand.jpeg)

### 🎯 Feature Importance

This visualization shows the relative importance of the features used by the **XGBoost model**, highlighting which variables contribute most to demand predictions.

![Feature Importance](images/feature_importance.jpeg)

### 📢 Promotion Impact on Demand

This visualization explores the relationship between promotional activity and demand, providing insights into how promotional campaigns can influence product demand.

![Promotion Impact](images/promotion_impact.jpeg)

## 🤖 Machine Learning Model

The project uses **XGBoost**, a gradient boosting algorithm well suited for structured/tabular data and regression problems.

The model is trained using engineered product and business features to learn patterns from historical demand and generate demand predictions.

The trained model is serialized using **Pickle**, allowing it to be reused without retraining.

## ⚙️ Machine Learning Workflow

1. Import and explore the dataset
2. Perform data cleaning and preprocessing
3. Conduct exploratory data analysis (EDA)
4. Analyze demand trends and business relationships
5. Engineer relevant features
6. Encode categorical variables
7. Split the dataset into training and testing sets
8. Train the XGBoost model
9. Evaluate model performance
10. Analyze feature importance
11. Serialize the trained model and encoders
12. Build a reusable prediction pipeline
13. Deploy the model through Streamlit

## 🖥️ Streamlit Application

The project includes an interactive **Streamlit web application** that allows users to provide relevant product and business inputs and receive a predicted demand value from the trained XGBoost model.

The application loads the serialized model and label encoders, processes user inputs using the same preprocessing pipeline used during training, and generates predictions in real time.

## 💾 Model Serialization

The trained machine learning components are saved for reuse:

* `xgb_model.pkl` — trained XGBoost model
* `label_encoders.pkl` — categorical feature encoders

This allows the Streamlit application to generate predictions without retraining the model.

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/maliksubhanameerali/demand-forecasting.git
```

Navigate into the project directory:

```bash
cd demand-forecasting
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost streamlit
```

Run the notebook:

```bash
jupyter notebook
```

## ▶️ Run the Streamlit Application

After installing the required dependencies, run:

```bash
streamlit run app.py
```

The application will open in your browser and provide an interactive interface for generating demand predictions.

## 🔮 Future Improvements

* Hyperparameter tuning
* Cross-validation
* Advanced time-series features
* Model comparison with other regression algorithms
* Additional forecasting metrics
* Time-series forecasting models
* Improved Streamlit dashboard
* Real-time demand monitoring
* Automated model retraining
* Cloud deployment
* REST API integration

## 📚 Learning Outcomes

This project strengthened my understanding of:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Regression algorithms
* XGBoost
* Machine learning model evaluation
* Data visualization
* Feature importance analysis
* Model serialization with Pickle
* Building reusable ML pipelines
* Streamlit application development
* End-to-end machine learning deployment

## 👨‍💻 Author

**Malik Subhan Ameer Ali**

Aspiring AI & Machine Learning Engineer passionate about building intelligent, data-driven solutions using Python and machine learning.

**GitHub:** https://github.com/maliksubhanameerali

**LinkedIn:** https://www.linkedin.com/in/malik-subhan-ameer-ali-3b0061416
