This notebook uses Logistic Regression to predict individual medical insurance costs based on demographic and health-related features. It covers the full workflow from data loading and exploration, through preprocessing and feature engineering, to model training, evaluation, and interpretation.

**Key objectives:**

* Understand the relationships between features (age, gender, BMI, smoking status, region, number of children) and insurance charges.
* Prepare the dataset for modeling via cleaning, encoding categorical variables, and scaling numeric features.
* Train Logistic Regression to identify the best predictor of insurance cost.
* Evaluate model performance using appropriate metrics (MSE and R²).
* Interpret model outputs and derive insights.

### 2. File Structure

* **Predicting Insurance Cost.ipynb**: Main notebook containing code and narrative.
* **data/insurance.csv**: CSV dataset used in the analysis.

### 3. Dependencies

Ensure you have the following libraries installed:

```bash
pandas
numpy
matplotlib
seaborn
scikit-learn

```

### 4. Notebook Sections

The notebook is divided into the following sections:

1. **Imports & Settings**

   * Load necessary Python libraries and configure plotting styles.

2. **Data Loading**

   * Read the `insurance.csv` file into a Pandas DataFrame and display initial rows.

3. **Exploratory Data Analysis (EDA)**

   * Summary statistics of features.
   * Visualizations:

     * Distribution of insurance charges.
     * Scatter plots relating age, BMI, and charges.
     * Box plots for categorical factors (smoking status, region, gender).

4. **Train-Test Split**

   * Split the dataset into training and testing sets (default 80/20).

5. **Model Training**

   * Regression model to evaluate:

     * Linear Regression

6. **Model Evaluation**

   * Calculate metrics: Mean Squared Error (MSE), R² Score.

7. **Feature Importance & Interpretation**

   * Extract feature importances and visualize the top predictors.
   * Discuss how features impact insurance cost predictions.

8. **Conclusion**

    * Summarize key findings.
