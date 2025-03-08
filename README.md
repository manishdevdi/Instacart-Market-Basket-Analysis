# 📊 Instacart Market Basket Analysis

### 🚀 Project Overview

Instacart Market Basket Analysis aims to uncover customer purchasing behavior by analyzing transactional data. This project applies data science techniques to extract meaningful insights from customer orders, helping businesses optimize product recommendations and inventory management.

### 📌 Key Objectives

- Understand purchasing patterns of Instacart customers.

- Identify frequently bought items together using association rule mining.

- Segment customers based on their buying habits.

- Predict future purchases using machine learning models.

### 📂 Dataset

The dataset is sourced from Instacart’s open [data](https://www.kaggle.com/c/instacart-market-basket-analysis/data), containing 3 million grocery orders from 200,000 users. The dataset includes:

- order_products_prior.csv - Prior orders of users

- orders.csv - Order metadata

- products.csv - Product details

- aisles.csv - Aisle details

- departments.csv - Department details

### Project Structure
```
.
├── Plots/                                      : Contains all plots 
├── Data Description and Analysis.ipynb         : Initial analysis to understand data
├── Exploratory Data Analysis.ipynb             : EDA to analyze customer purchase pattern
├── Customers Segmentation.ipynb                : Customer Segmentation based on product aisles
├── Market Basket Analysis.ipynb                : Market Basket Analysis to find products association
├── Feature Extraction.ipynb                    : Feature engineering and extraction for a ML model
├── Data Preparation.ipynb                      : Data preparation for modeling
├── ANN Model.ipynb                             : Neural Network model for product reorder prediction
├── XGBoost Model.ipynb                         : XGBoost model for product reorder prediction
├── LICENSE                                     : License
└── README.md                                   : Project Report
```
<br />
This project structure offers a systematic approach, breaking down tasks into manageable steps, with each notebook focusing on a specific task in the data analysis and modeling pipeline.

## 📈 Methods Used
- **Data Cleaning:** Handled missing values and outliers.
- **Exploratory Data Analysis (EDA):** Visualizations using Matplotlib and Seaborn.
- **Association Rule Mining:** Applied Apriori algorithm for product recommendations.
- **Clustering:** K-means clustering for customer segmentation.
  
## ⚙️ Installation & Setup

   Clone the repository and install dependencies:
### Clone this repository
git clone https://github.com/manishdevdi/Instacart-Market-Basket-Analysis.git
cd instacart-market-basket-analysisInstall dependencies

### Install required libraries
[pip install -r requirements.txt](https://github.com/manishdevdi/Instacart-Market-Basket-Analysis/blob/main/requirements.txt)

## 🚀 Future Improvements

- Implement deep learning-based recommendation models.

- Improve data cleaning for better accuracy.

- Analyze seasonal trends in purchases.

- Integrate with real-time transaction data for live recommendations.
  
## 🤝 Contributing

Contributions are welcome! Feel free to submit issues, feature requests, or pull requests to improve the project.

## 📜 License

This project is licensed under the MIT License.

## 📬 Connect with Me

💼 [LinkedIn](https://www.linkedin.com/in/manish-devdi-63bb78234/) 

## 🌟 If you found this project useful, don’t forget to star ⭐ the repository!


    
