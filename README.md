# 🛒 Walmart Sales Forecast

![Walmart Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/Walmart_logo.svg/320px-Walmart_logo.svg.png)

## 📝 Background

Accurate sales forecasting is crucial for large retailers like Walmart to optimize inventory, staffing, and supply chain operations. By leveraging historical sales data and advanced machine learning models, this project seeks to provide actionable insights that can support business decision-making and improve operational efficiency.

## 📊 Project Overview

This project aims to forecast Walmart's weekly sales using historical data and machine learning techniques. By analyzing various factors such as store details, department information, and external influences like holidays, I strive to predict future sales accurately.

## 🎯 Objectives

- Analyze historical Walmart sales data
- Identify key factors influencing sales
- Develop and compare multiple forecasting models
- Provide accurate weekly sales predictions

## 🗃️ Dataset

The project utilizes the following datasets:
- `stores.csv`: Store information
- `features.csv`: Additional features like temperature, fuel price, etc.
- `train.csv`: Historical sales data

Key features include:
- Store and department identifiers
- Date
- Weekly sales
- Is_holiday flag
- Temperature, fuel price, CPI, and unemployment rate

## 🛠️ Methodology

1. **Data Preprocessing**
   - Merging datasets
   - Handling missing values
   - Feature engineering (e.g., extracting year, month, week)

2. **Exploratory Data Analysis (EDA)**
   - Visualizing sales trends
   - Analyzing correlations between features
   - Identifying seasonal patterns

3. **Model Implementation**
   We implement and compare the following models:
   - Linear Regression
   - Random Forest Regressor
   - XGBoost Regressor

4. **Model Evaluation**
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)
   - R-squared (R2) score

## 💻 Tech Stack

- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost

## 🚀 Getting Started

1. Clone the repository:
2. Install required dependencies:
3. Open and run the Jupyter Notebook `Walmart_Sales_Forecast.ipynb`

## 📈 Results

My models show promising results in predicting Walmart's weekly sales. 

*Example results:*
- **Random Forest Regressor:** RMSE = 7550.82, R² = 0.89
- **XGBoost Regressor:** RMSE = 3565.72, R² = 0.97

Detailed performance metrics and visualizations are available in the Jupyter Notebook.

## ⚠️ Limitations

- The analysis is based on historical data and may not account for unforeseen events (e.g., pandemics, economic shifts).
- Model predictions may not generalize to stores or departments not well represented in the training data.
- External factors beyond the provided features (e.g., local promotions, competitor actions) are not included.

## 🔮 Future Enhancements

- Incorporate more external data sources (e.g., economic indicators)
- Experiment with time series models (ARIMA, Prophet)
- Develop a web dashboard for interactive sales forecasting

## 🤝 Contributing

I welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b feature-branch`
3. Make your changes and commit: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-branch`
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.txt) file for details.

## 📞 Contact

For any queries or suggestions, please contact:
Vaikunth Desai - vdclassifier@gmail.com

---

⭐️ If you find this project helpful, please give it a star!
