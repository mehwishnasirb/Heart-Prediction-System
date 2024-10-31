# Heart-Prediction-System
This project provides a comprehensive analysis and prediction system for heart failure using a diverse dataset that includes patient demographics, lifestyle factors, and clinical data. The primary goal is to predict the occurrence of heart failure and examine the impact of various factors. 
# Heart Failure Prediction and Analysis

This project provides an in-depth analysis and prediction system for heart failure using a dataset that includes patient demographic, lifestyle, and clinical data. The main focus is on predicting heart failure occurrence and understanding the influence of various features. The project leverages data visualization, feature engineering, and machine learning models to produce a robust analysis pipeline.

## Project Structure and Features

### 1. Data Loading and Preprocessing
- The dataset is loaded from an Excel file, and relevant features are extracted.
- Basic data cleaning and preprocessing are performed to ensure compatibility with machine learning models.
- Features are categorized as continuous or categorical, aiding in tailored preprocessing steps.

### 2. Exploratory Data Analysis (EDA)
- **Visualization**: The data is analyzed using histograms, count plots, and distribution plots to examine continuous and categorical variables.
- **Feature Analysis**: Specific attributes, like `Age`, `RestingBP`, `Cholesterol`, etc., are analyzed to understand their distribution and relevance to heart failure.
- **Categorical Insights**: Count plots explore the distribution across different categories, such as `Sex`, `ChestPainType`, and `ST_Slope`, which provide insights into their relationship with heart failure.

### 3. Machine Learning Models
- **Feature Selection**: SelectKBest is employed to identify the most impactful features for classification.
- **Model Selection and Evaluation**: RandomForest, Gradient Boosting, and Decision Tree classifiers are trained and evaluated using metrics like ROC-AUC, accuracy, F1-score, and confusion matrix to determine the best-performing model.

### 4. Profiling and Report Generation
- A profiling report is generated for a comprehensive overview of the dataset using `ydata_profiling`, providing insights into data quality and distributions.

### 5. Visualization
- Additional visualizations are created to show trends and correlations in the data, with emphasis on features such as `Sex`, `ChestPainType`, and `Fasting Blood Sugar`.

## Installation

```bash
# Clone this repository
git clone <repo-url>

# Install required packages
pip install -r requirements.txt
