# Heart Disease Prediction Project

## Overview

This project aims to predict the presence of heart disease using the Cleveland heart disease dataset. By leveraging various machine learning algorithms, we developed models to assist healthcare professionals in making informed diagnostic decisions. The project evaluates the performance of multiple algorithms and explores potential enhancements for future work.

## EDA

Exploratory Data Analysis (EDA)
In this project, we performed an Exploratory Data Analysis (EDA) to understand the structure and distribution of the dataset. The key steps in the EDA included:

Descriptive Statistics: We used methods such as .describe() and .info() to summarize the dataset's characteristics, including data types, missing values, and statistical measures (mean, median, mode, etc.).

Visualization: Several visualizations were created to explore data distributions and relationships between features:
- Histograms for numerical features like age.
- Pie charts and count plots for categorical features like sex and dataset location.
- Correlation matrix to identify potential relationships between numerical variables.
  
Missing Data Handling: We identified and accounted for missing values in features like trestbps, chol, slope, and ca.

The EDA was applied to all features in the dataset, ensuring a comprehensive understanding of the data before proceeding to the preprocessing stage.

## Key Findings

- **XGBoost**: Achieved the highest test accuracy of 86.96%, demonstrating strong predictive power and generalizability.
- **Random Forest**: Test accuracy of 83.70%, indicating robust performance but slight overfitting.
- **SVM**: Test accuracy of 82.97%, effectively finding optimal hyperplanes for classification.
- **KNN**: Test accuracy of 84.42%, capturing local patterns effectively.
- **Naive Bayes**: Test accuracy of 83.33%, providing a good balance between bias and variance.
- **Logistic Regression**: Test accuracy of 84.42%, offering straightforward and efficient predictions.

## Future Work

Potential enhancements for the predictive models include:
- **Ensemble Learning**: Implementing advanced methods like stacking to combine multiple models for improved performance.
- **Deep Learning**: Exploring CNNs and RNNs to capture complex patterns and temporal relationships.
- **Feature Engineering**: Developing sophisticated techniques to capture non-linear relationships.
- **Model Interpretability**: Utilizing SHAP values to align model predictions with medical expertise.
- **Class Imbalance Handling**: Applying methods such as SMOTE or cost-sensitive learning to improve performance on minority classes.
- **Integration of Additional Data**: Incorporating genetic, lifestyle, and longitudinal health data for more comprehensive models.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/heart-disease-prediction.git
    cd heart-disease-prediction
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv env
    source env/bin/activate   # On Windows, use `env\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Ensure the Cleveland heart disease dataset is available in the project directory.
2. Run the Jupyter notebooks to preprocess the data, train models, and evaluate performance:
    ```sh
    jupyter notebook
    ```
3. Follow the notebooks for detailed steps on data preprocessing, model training, and evaluation.

## Results

The project results are summarized in the final report and detailed in the Jupyter notebooks. Model performance metrics and visualizations are provided for each algorithm.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or new features.

