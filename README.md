# Staff Attrition Analysis Using Machine Learning

## Introduction

Employee attrition refers to an employee’s voluntary or involuntary resignation from a workforce. Organizations invest significant resources in hiring and training employees, making every individual crucial to a company’s success. Our goal was to predict employee attrition and identify key factors contributing to workforce departures. We trained multiple classification models on our dataset and assessed their performance using metrics such as accuracy, precision, recall, and F1 score. Additionally, we analyzed the dataset to extract insights into the driving factors of attrition, aiding organizations in improving retention rates.

## Methodology

The analysis follows a structured methodology:

1. **Data Preprocessing and Exploration**
2. **Feature Engineering**
3. **Model Training and Evaluation**
4. **Hyperparameter Tuning**
5. **Model Interpretability and Insights**

## Machine Learning Models

We trained and evaluated nine supervised machine learning classification models:

- Logistic Regression
- Naive Bayes
- Decision Tree
- Random Forest
- AdaBoost
- Support Vector Machine
- Linear Discriminant Analysis
- Multilayer Perceptron
- K-Nearest Neighbors

## Datasets

To ensure robust model performance, we trained our models on six different dataset variations:

- **Imbalanced**
- **Undersampled**
- **Oversampled**
- **PCA-transformed**
- **Undersampling with PCA**
- **Oversampling with PCA**

Hyperparameter tuning was performed using **RandomSearchCV** and **GridSearchCV**, along with **5-fold cross-validation**. Model performance was evaluated using accuracy, precision, recall, and F1 Score, considering accuracy alone can be misleading in imbalanced datasets.

## Dataset

We utilized the **IBM Employee Attrition dataset** from Kaggle, consisting of **35 columns** and **1470 rows** with a mix of numerical and categorical features. A sample row includes attributes such as:

- **Age**
- **MonthlyIncome**
- **OverTime**
- **BusinessTravel**
- **PerformanceRating**

## Installation & Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/staff-attrition-analysis.git
   cd staff-attrition-analysis
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis:
   ```bash
   python main.py
   ```

## Contributing

Currently -Shreshthav Bisht (voidGlitch)
Contributions are welcome! Feel free to submit issues or create pull requests.

## License

This project is licensed under the MIT License.
