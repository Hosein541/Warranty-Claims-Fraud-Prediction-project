## Project Overview
The aim of this data science project is to predict the authenticity of warranty claims by analyzing various factors such as region, product category, claim value, and more. The dataset used for this project was sourced from Kaggle and comprises 358 rows and 21 columns

## Summary and Conclusion 
Data Preprocessing Steps
1. Categorical Data Reduction: Decreased the number of categories in categorical columns to simplify the dataset.
2. Feature Engineering: Modified one of the columns to increase model correlation and improve predictive power.
3. Data Visualization: Conducted exploratory data analysis to gain insights into the dataset's characteristics.
4. Data Standardization: Normalized numerical features to ensure consistent scale across variables.
5. Categorical Encoding: Implemented label encoding for categorical variables to prepare them for machine learning algorithms.

### Model Performance Enhancement

Initial model evaluation showed suboptimal results. To address this issue, we implemented the ADASYN (Adaptive Synthetic) method.

### ADASYN Implementation

By employing the ADASYN method, we significantly increased the number of samples for minority classes. This resampling technique led to a substantial enhancement in the model's predictive accuracy. The rebalanced dataset resulted in improved performance in predicting fraudulent warranty claims.

### Key Findings

1. ADASYN effectively addressed the class imbalance problem in our dataset.
2. The balanced data led to a more robust and accurate prediction model.
3. The model's ability to identify fraudulent warranty claims improved considerably.

## Conclusion

These findings demonstrate that utilizing class balancing techniques like ADASYN can significantly enhance the performance of fraud prediction models. We recommend employing ADASYN and machine learning models trained using this method for analyzing and predicting warranty claims fraud, as it can lead to improved accuracy and predictive capability of the models.

### Developer Information

Developed by Hosein Mohammadi

- GitHub: [https://github.com/Hosein541](https://github.com/Hosein541)
- LinkedIn: https://www.linkedin.com/in/hosein-mohammadi-979b8a2b2/
- Email: Huseinmohammadi83@gmail.com
