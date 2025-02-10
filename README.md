
# Employee Retention Predictor

This project aims to analyze employee attrition in a pharmaceutical company, leveraging machine learning (ML) techniques to identify factors influencing employee turnover. By using classification models, the goal is to predict employees who might leave the company and suggest areas for improvement to increase retention rates.

### Table of Contents
1. [Dataset Loading and Initial Analysis](#1.-Dataset-Loading-and-Initial-Analysis)
2. [Data Merging and Comprehensive Analysis](#2.-Data-Merging-and-Comprehensive-Analysis)
3. [Data Imputation Process](#3.-Data-Imputation-Process)
4. [Data Encoding Process](#4.-Data-Encoding-Process)
5. [Feature Scaling](#5.-Feature-Scaling)
6. [Feature Selection](#6.-Feature-Selection)
7. [Model Evaluation and Selection](#7.-Model-Evaluation-and-Selection)
8. [Hyperparameter Tuning](#8.-Hyperparameter-Tuning)
9. [Fitting the Model and Performance Evaluation](#9.-Fitting-the-Model-and-Performance-Evaluation)
10. [Cross Validation in Model Evaluation](#10.-Cross-Validation-in-Model-Evaluation)
11. [Performance Analysis of Classifiers](#11.-Performance-Analysis-of-Classifiers)
12. [Interpretation of Results](#12.-Interpretation-of-Results)

## Project Overview

The project uses employee data from various sources, including survey results, general data, and performance reviews, to develop a predictive model that determines the likelihood of employee attrition. The process involves the following key steps:

1. **Dataset Loading and Initial Analysis**: Importing and summarizing each dataset to understand the structure and potential issues.
2. **Data Merging and Comprehensive Analysis**: Combining multiple datasets based on employee identifiers and performing a deeper analysis to understand relationships.
3. **Data Imputation**: Handling missing data with KNN for numeric columns and Random Forest for categorical columns to ensure a complete dataset.
4. **Data Encoding**: Encoding categorical variables using One-Hot Encoding and Label Encoding to prepare the data for ML models.
5. **Feature Scaling**: Applying **RobustScaler** to scale features, mitigating the impact of outliers, especially in salary and performance-related metrics.
6. **Feature Selection**: Selecting relevant features to improve model performance.
7. **Model Evaluation and Selection**: Testing multiple classification models to predict employee attrition, evaluating them based on various performance metrics.
8. **Hyperparameter Tuning**: Fine-tuning the models to optimize their performance.
9. **Performance Evaluation**: Assessing the final model using metrics like accuracy, precision, recall, and F1-score.
10. **Cross-Validation**: Implementing cross-validation to ensure the model’s generalizability.
11. **Performance Analysis**: Comparing the results of different models to select the best one.
12. **Interpretation of Results**: Understanding the final model’s predictions and providing actionable insights for the company.

## Installation

To run this project, ensure you have Python 3.x installed. Then, install the required dependencies using the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Employee-Retention-Predictor.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Employee-Retention-Predictor
   ```
3. Execute the Jupyter notebook to view the detailed analysis and results:
   ```bash
   jupyter notebook
   ```

## Data Sources

The datasets used in this project come from anonymized employee records provided by the Human Resources department of a pharmaceutical company. These include general employee information, survey results, and performance assessments.

## Contributing

Feel free to fork this repository and submit pull requests. If you have suggestions for improvements, please open an issue!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
