# A Preliminary Study of Applying Machine Learning Algorithms in Predicting Dementia

This repository contains the R and Python code for my capstone project, which systematically compares the performance of different machine learning models XGBoost, Random Forest, and Neural Networks in predicting dementia.

---

## Repository Contents

The repository includes four main scripts. They are organized to reflect the workflow of the project:

1. **`data.merge`**  
   - Combines cognitive and phone-tapping data into a single tabular dataset.

2. **`data.normalization`**  
   - Examines feature distributions before and after normalization.  
   - Compares the performance of **Standard Normalization** and **Seo-Johnson Normalization**.

3. **`neural_network`**  
   - Defines a **sum-of-weights method** for feature importance in multi-layer neural networks.  
   - Provides feature importance visualizations across different network structures.  
   - Evaluates model behavior by comparing statistical properties on the test set.

4. **`model_comparison`**  
   - Compares the predictive performance of **XGBoost, Random Forest, and Neural Networks**.  
   - Includes **hyperparameter tuning**, **feature importance visualization**, **cross-validated SHAP analysis**, **cross-validated ROC curves**, and **cumulative AUC** with respect to features added.

---

## How to Run

1. Clone this repository.  
2. Open the scripts in R or Python.  
3. Install required libraries/packages as prompted.  
4. Run the scripts in the order listed above.

---

## Notes

- The project focuses on **feature importance analysis** and **model performance evaluation** for dementia prediction.  
- Scripts are designed to be modular, so each step can be inspected independently.  

