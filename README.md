# CardioInsight: Machine Learning-Based Heart Risk Prediction

## Project Overview
CardioInsight is an advanced machine learning project designed to predict cardiovascular risk in patients using clinical data. By analyzing key features such as age, cholesterol levels, and chest pain type, the system identifies high-risk individuals with remarkable accuracy, supporting early detection and preventive care. The project uses a Random Forest Classifier as the primary model along with feature selection techniques to ensure reliable and interpretable predictions.  

Multiple models were trained and evaluated, including **Logistic Regression, Decision Tree, K-Nearest Neighbors, Support Vector Machine, and Random Forest**, to select the best-performing model for deployment. Detailed evaluation metrics were recorded to compare performance and reliability.

## Key Features
- **High-Performance Prediction**: Achieves over 98% test accuracy with Random Forest.  
- **Insightful Feature Analysis**: Identifies the most significant clinical features affecting heart disease risk.  
- **Data Visualization**: Correlation heatmaps, feature importance plots, and model evaluation charts included.  
- **Scalable & Modular**: Easily adaptable to new datasets or alternative ML models.  
- **Multi-Model Evaluation**: Allows comparison of multiple models to select the most effective one.  

## Trained Models & Metrics
| Model               | Accuracy | Precision | Recall  | F1-Score |
|----------------------|----------|-----------|---------|----------|
| Logistic Regression  | 86.6412  | 83.8509   | 93.75   | 88.5246  |
| Decision Tree        | 97.3282  | 97.2414   | 97.9167 | 97.5779  |
| **Random Forest**    | **98.4733** | **97.2973** | **100**   | **98.6301** |
| Gradient Boosting    | 96.9466  | 95.9459   | 98.6111 | 97.2603  |
| SVM                  | 89.6947  | 87.7419   | 94.4444 | 90.9699  |
| KNN                  | 87.0229  | 89.2857   | 86.8056 | 88.0282  |


## Top Features
The following features were found to be most important in predicting heart disease risk:  
- **Age**  
- **Cholesterol levels**  
- **Chest pain type (Typical angina)**  


## How to Use

1. **Clone the repository:**
```bash
git clone https://github.com/Abubakar-Shabbir/HeartScope-Predictive-ML-for-Cardiovascular-Risk.git
```

2. **Install the dependencies:**
```bash
pip install -r requirements.txt
```
3. **Open the Jupyter Notebook**
Navigate to the notebook file to explore data analysis, modeling, and visualizations:
Notebooks/HeartScope_Predictive ML for Cardiovascular Risk.ipynb

## Author

Abubakar Shabbir

## License
This project is licensed under the [MIT License](./LICENSE).
