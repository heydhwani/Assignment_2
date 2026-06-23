# Titanic Data Preprocessing and Survival Analysis

## Project Overview

This project focuses on cleaning, preprocessing, and analyzing the Titanic dataset using Python. The objective is to handle missing values, transform categorical variables, normalize numerical features, and generate meaningful insights about passenger survival through data visualization.

---

## Dataset Information

The dataset contains passenger information from the Titanic disaster, including demographic details, ticket information, travel class, and survival status.

### Key Features

* PassengerId
* Survived
* Pclass
* Sex
* Age
* SibSp
* Parch
* Fare
* Embarked

### Dataset Size

* Total Records: 891
* Original Features: 12
* Processed Features: 9

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Data Preprocessing Steps

### Missing Value Treatment

* Age missing values filled using median age.
* Embarked missing values filled using mode.
* Cabin column removed due to excessive missing values.

### Encoding

* Sex column encoded using Label Encoding.
* Embarked column encoded using Label Encoding.
* Pclass was already in numerical format and required no additional encoding.

### Feature Selection

The following columns were removed:

* Name
* Ticket
* Cabin

### Normalization

Min-Max Scaling was applied to:

* Age
* Fare

---

## Visualizations Performed

1. Survival Distribution
2. Gender Ratio Analysis
3. Gender vs Survival
4. Passenger Class vs Survival
5. Age vs Survival
6. Fare vs Survival

---

## Key Findings

### Gender Influenced Survival

Female passengers had significantly higher survival rates than male passengers.

### Passenger Class Affected Survival

First-class passengers showed better survival outcomes compared to second and third-class passengers.

### Fare Was Associated with Survival

Passengers paying higher fares generally had better survival chances.

### Age Was Not the Strongest Predictor

Age showed some variation across groups but had less influence than gender and passenger class.

### Survival Patterns Were Uneven

Survival outcomes varied considerably across demographic and socioeconomic groups.

---

## Repository Structure

Assignment_2/

├── data/

│   ├── train.csv

│   └── titanic_cleaned.csv

│

├── notebooks/

│   └── titanic_analysis.ipynb

│

├── reports/

│   └── insights_note.md

│

├── requirements.txt

├── README.md

└── .gitignore

---

## Conclusion

This project demonstrates a complete data preprocessing workflow, including missing value treatment, encoding, normalization, visualization, and insight generation. The analysis highlights how factors such as gender, passenger class, and fare influenced passenger survival and showcases the importance of preprocessing before performing data analysis.
