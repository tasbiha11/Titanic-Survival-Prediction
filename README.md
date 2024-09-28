# Titanic Survival Prediction Using OpenML Dataset

## Project Overview
This project predicts the survival of passengers aboard the Titanic using a machine learning model. The dataset provides information about the passengers' demographics and ticket details. The project involves data preprocessing, model building, and performance evaluation using the Naïve Bayes algorithm.

## Dataset
- **Dataset Used**: Titanic dataset from [OpenML](https://www.openml.org/d/40945), originally provided by Vanderbilt University's Department of Biostatistics.
- **Dataset Source**: [Vanderbilt University's Department of Biostatistics](https://hbiostat.org/data).
- **Features**:
  - `Pclass`: Ticket class
  - `Sex`: Gender
  - `Age`: Age of passengers
  - `SibSp`: Number of siblings or spouses aboard the Titanic
  - `Parch`: Number of parents or children aboard the Titanic
  - `Fare`: The ticket fare
  - `Embarked`: Port of Embarkation
  - `Survived`: Whether the passenger survived or not (target variable)

## Project Steps

### Step 1: Data Preprocessing and Cleaning
- Handled missing values in the `Age` and `Embarked` columns.
- Categorical variables (e.g., `Sex`, `Embarked`) were converted into numerical format for the machine learning model.

### Step 2: Exploratory Data Analysis (EDA)
- Plotted various passenger characteristics and their relation to survival.
- Visualized survival rates across different ticket classes, gender, and age using **Matplotlib**.

![Survival by Class and Gender](![Plot](./output.png)
)  <!-- Replace with the actual file path to your image -->

### Step 3: Model Building
- **Model Used**: Naïve Bayes
- Trained the model using the preprocessed dataset to predict passenger survival.

### Step 4: Model Evaluation
- Evaluated the model using accuracy as the main metric.
- **Accuracy**: The model achieved a **75% accuracy** in predicting whether a passenger would survive.

## Requirements
- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - (Optional) `Jupyter Notebook`

You can install the required libraries using:
```bash
pip install -r requirements.txt
