# Heart Disease Prediction using Logistic Regression

This project uses machine learning techniques to predict the presence of heart disease based on clinical data. It employs logistic regression, a widely-used statistical model for binary classification tasks.

## Overview

The goal is to build a predictive model that can classify whether a patient has heart disease based on features such as age, sex, chest pain type, blood pressure, cholesterol level, and other relevant medical attributes.

## Dataset

The dataset used in this notebook is `heart_disease_data.csv`, which should be placed in the same directory as the notebook. It is expected to contain no missing values in the final model-ready version.

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn

## Workflow

1. **Data Loading and Exploration**
   - Load the dataset with pandas
   - Inspect data structure and check for missing values

2. **Data Preprocessing**
   - Clean and prepare data for model training

3. **Model Building**
   - Use Logistic Regression for binary classification
   - Split the dataset into training and testing sets

4. **Model Evaluation**
   - Measure model performance using accuracy

## How to Run

1. Clone the repository or download the `.ipynb` file
2. Make sure `heart_disease_data.csv` is in the same directory
3. Install the required libraries:
   ```bash
   pip install numpy pandas scikit-learn
   ```
4. Run the notebook using Jupyter:
    ```bash
    jupyter notebook main.ipynb
    ```

## Results

The logistic regression model achieves reasonable accuracy, providing a foundation for more advanced modeling or integration into clinical decision support systems

## License

This project is open-source and available under the MIT License.