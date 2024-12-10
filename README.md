
# Disease Prediction Using Machine Learning

This project demonstrates the use of machine learning models to predict disease outcomes based on patient data. It includes data preprocessing, exploratory analysis, model training, and performance evaluation.

---

## Prerequisites

### System Requirements
- Python 3.7 or higher

### Required Libraries
Install the required libraries using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## How to Run

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Prepare the Dataset**:
   - Place the dataset file (e.g., `heart_disease_dataset.csv`) in the project directory.

3. **Run the Script**:
   Execute the Python script to preprocess the data, analyze features, train models and evaluate their performance:
   ```bash
   python disease_prediction.py
   ```

4. **Outputs**:
   - **Visualizations**: Histograms, scatter plots, and heatmaps.
   - **Metrics**: Accuracy, precision, recall and F1-score.
   - **Model Performance Comparison**: A summary table highlighting the best-performing model.

---

## Insights Gained

### Data Analysis
1. **Feature Importance**:
   - Variables like `cholesterol` and `age` showed significant relationships with the target variable.
2. **Class Imbalance**:
   - The dataset had some imbalance, which was managed during evaluation.

### Model Performance
| Model                 | Accuracy | Precision | Recall | F1-Score |
|-----------------------|----------|-----------|--------|----------|
| Logistic Regression   | 81.82%  | 82.42%    | 81.82% | 81.69%   |
| Random Forest         | 99.03%  | 99.05%    | 99.03% | 99.03%   |
| Support Vector Machine| 84.74%  | 85.48%    | 84.74% | 84.62%   |

- **Random Forest** emerged as the best-performing model with outstanding accuracy and balanced metrics.

### Recommendations
1. Deploy **Random Forest** for its superior performance and reliability.
2. Further optimize predictions by:
   - Hyperparameter tuning.
   - Adding more data or engineered features.

---

## Visualizations
1. **Histograms and Density Plots**:
   - Highlight feature distributions and variations.
2. **Scatter and Pairplots**:
   - Showcase relationships between key variables.
3. **Correlation Heatmap**:
   - Identify multicollinearity and significant predictors.

---

## Conclusion

This project effectively predicts disease outcomes using machine learning. The insights derived can assist healthcare professionals in early detection and prioritizing at-risk individuals. Future improvements include scaling the dataset and incorporating advanced techniques for even better performance.

---
