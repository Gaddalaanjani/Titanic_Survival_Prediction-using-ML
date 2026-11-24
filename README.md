# Titanic Survival Prediction Using Machine Learning

## Project Overview

The **Titanic Survival Prediction** project uses Machine Learning classification algorithms to predict whether a passenger survived the Titanic disaster based on passenger information such as age, gender, passenger class, fare, and family details.

The main goal of this project is to understand the complete Machine Learning workflow, including data cleaning, exploratory data analysis, feature engineering, model building, and evaluation.

##  Project Objective

- Analyze passenger information to identify survival patterns.
- Perform data cleaning and preprocessing.
- Explore relationships between passenger features and survival.
- Build Machine Learning classification models.
- Evaluate and compare model performance.
- Predict the survival probability of a new passenger.

## Dataset

**Dataset:** Titanic - Machine Learning from Disaster  
**Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)

The training dataset contains:

| Description | Count |
|---|---:|
| Total passengers | 891 |
| Survived | 342 |
| Did not survive | 549 |

### Important Features

| Feature | Description |
|---|---|
| PassengerId | Unique passenger identification |
| Pclass | Passenger class (1, 2, 3) |
| Sex | Passenger gender |
| Age | Passenger age |
| SibSp | Number of siblings/spouses aboard |
| Parch | Number of parents/children aboard |
| Fare | Ticket fare |
| Embarked | Port of embarkation |
| Survived | Target variable (0 = No, 1 = Yes) |

## 🛠️ Technologies Used

- **Python** – Programming language
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Scikit-learn** – Machine Learning model development
- **Jupyter Notebook** – Development environment

## 🔄 Project Workflow

### 1. Data Loading
- Imported the Titanic dataset using Pandas.
- Examined dataset dimensions, columns, and data types.

### 2. Exploratory Data Analysis (EDA)
- Analyzed survival distribution.
- Studied survival patterns based on gender and passenger class.
- Visualized relationships using charts and graphs.

### 3. Data Cleaning and Preprocessing
- Identified missing values in Age, Cabin, and Embarked.
- Handled missing values using appropriate imputation techniques.
- Encoded categorical variables.
- Applied feature scaling where required.

### 4. Feature Engineering
Created additional features to improve model learning:

- **Title:** Extracted passenger titles from names.
- **FamilySize:** Combined SibSp and Parch information.
- **IsAlone:** Identified passengers travelling alone.
- **Has_Cabin:** Indicated whether cabin information was available.

### 5. Model Building

Implemented and compared the following classification algorithms:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### 6. Model Evaluation

Evaluated model performance using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score
- Cross-Validation

### 7. Prediction

Used the trained model to predict whether a new passenger would survive.

A sample prediction from the project:

- **Prediction:** Passenger Survived
- **Survival Probability:** 95.54%

*Note: This probability belongs to one sample passenger prediction. It is not the overall model accuracy.*

## Key Learnings

- Understanding the end-to-end Machine Learning lifecycle.
- Handling missing values and categorical variables.
- Performing exploratory data analysis.
- Creating meaningful features through feature engineering.
- Building classification models using Scikit-learn.
- Evaluating models using multiple performance metrics.
- Making predictions for new passenger records.

## Future Improvements

- Perform hyperparameter tuning to improve model performance.
- Experiment with advanced algorithms such as Gradient Boosting and XGBoost.
- Improve feature selection and engineering.
- Deploy the trained model using Streamlit or Flask.
- Build an interactive interface for passenger survival prediction.

## Project Structure

```text
Titanic_Survival_Prediction/
│
├── Titanic_ML_Project.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run This Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/Titanic-Survival-Prediction-ML.git
```

2. Navigate to the project directory:

```bash
cd Titanic-Survival-Prediction-ML
```

3. Install the required libraries:

```bash
pip install -r requirements.txt
```

4. Download the dataset from Kaggle and place `train.csv` in the project folder.

5. Open the Jupyter Notebook:

```bash
jupyter notebook
```

6. Open `Titanic_ML_Project.ipynb` and run the cells.

## Author

**Anjani Gaddala**

Aspiring Data Analyst | Machine Learning Enthusiast

Interested in Python, SQL, Data Analytics, Power BI, and Machine Learning.

---
If you find this project useful, feel free to star the repository!
