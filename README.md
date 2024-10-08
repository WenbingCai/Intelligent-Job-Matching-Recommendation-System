# Intelligent Job Matching Recommendation System

This project is an **Intelligent Job Matching Recommendation System** built using various machine learning algorithms, including Logistic Regression, Random Forest, and XGBoost. The system aims to provide accurate job matching recommendations based on user input data, improving recruitment efficiency by recommending the best-fit jobs for applicants.

## Project Structure

The project consists of multiple Jupyter notebooks, each detailing a specific aspect of the job recommendation system's development, training, and evaluation.

### Notebooks:
- **1. Data Preprocessing and Initial Model Setup**  
  Details the initial data preparation and feature engineering processes.
- **2. Model Training and Evaluation (Logistic Regression, Random Forest, XGBoost)**  
  A comprehensive walkthrough of training three different machine learning models (Logistic Regression, Random Forest, and XGBoost) to compare their performances.
- **3. Model Evaluation using MAP (Mean Average Precision)**  
  Evaluates the model performance using MAP, which is a key metric in ranking-based recommendation systems.

### Key Algorithms:
- **Logistic Regression**: A simple yet effective classification algorithm used for job matching.
- **Random Forest**: An ensemble method that improves performance by averaging multiple decision trees.
- **XGBoost**: A highly efficient and powerful implementation of gradient boosting used for achieving high accuracy.

## How to Run the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Intelligent-Job-Matching-Recommendation-System.git
    ```

2. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebooks to train and evaluate the models:
    ```bash
    jupyter notebook
    ```

4. Follow the steps in each notebook to preprocess the data, train the models, and evaluate performance metrics.

## Dependencies

- `scikit-learn` for model building
- `pandas` and `numpy` for data manipulation
- `matplotlib` for data visualization
- `xgboost` for implementing the XGBoost algorithm

You can install all dependencies by running:
```bash
pip install -r requirements.txt
