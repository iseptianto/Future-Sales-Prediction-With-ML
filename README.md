# 📊 Future Sales Prediction with Machine Learning

## 🔍 Overview
This project predicts future sales based on advertising expenditures across **TV, Newspaper, and Radio** using a **regression model**. The goal is to understand how different marketing channels impact sales and make data-driven decisions.

## 🚀 Features
- Predict sales based on advertising spend across different channels.
- Implement multiple regression techniques for accurate forecasting.
- Visualize the correlation between advertising mediums and sales.
- Deploy the model in a Flask web application for user interaction.

## 🏗️ Tech Stack
- **Python** (NumPy, Pandas, Scikit-learn, Matplotlib)
- **Machine Learning** (Linear Regression, Feature Engineering)
- **Flask** (For web deployment)
- **GitHub** (For version control)

## 📂 Project Structure
```
📦 Future-Sales-Prediction
├── 📁 data
│   ├── advertising.csv   # Dataset
├── 📁 models
│   ├── regression_model.pkl   # Trained ML model
├── 📁 flask_app
│   ├── app.py   # Flask application
├── requirements.txt   # Dependencies
├── README.md   # Project Documentation
```

## 🔢 Dataset
The dataset consists of the following columns:
- **TV**: Advertising budget spent on TV ads.
- **Newspaper**: Budget spent on newspaper ads.
- **Radio**: Budget spent on radio ads.
- **Sales**: The target variable representing revenue.

## 🧠 Machine Learning Approach
1. **Data Preprocessing**
   - Handle missing values, scale features, and encode categorical variables if necessary.
2. **Exploratory Data Analysis (EDA)**
   - Check correlations and visualize trends.
3. **Feature Selection**
   - Identify the most important predictors for sales.
4. **Regression Model**
   - Train a Linear Regression model to predict future sales.
5. **Model Evaluation**
   - Measure accuracy using metrics like R² score and Mean Squared Error (MSE).

## ⚙️ Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/iseptianto/Future-Sales-Prediction-With-ML.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Future-Sales-Prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Flask app:
   ```bash
   python flask_app/app.py
   ```
5. Access the web application at:
   ```
   http://127.0.0.1:5000/
   ```

## ✨ Results & Insights
- **TV advertising** might have the highest correlation with sales.
- **Newspaper advertising** could be less effective compared to TV and radio.
- The trained regression model provides future sales predictions based on input marketing budgets.

## 📌 Future Improvements
- Experiment with advanced regression techniques like **Polynomial Regression** or **Random Forest Regression**.
- Optimize hyperparameters to improve model performance.
- Expand dataset by integrating more factors like **social media ads, influencer marketing**, etc.
- Deploy the model using **Flask and Docker** for a scalable web service.

## 🤝 Contributing
Feel free to raise **issues**, submit **pull requests**, or suggest improvements. Let's build something great together! 🚀

## 📝 License
This project is licensed under the **MIT License** – free for personal and commercial use.

