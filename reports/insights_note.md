# Titanic Dataset – Insights Note

## Objective

The objective of this project was to preprocess, analyze, and visualize the Titanic dataset to identify factors that influenced passenger survival.

## Data Preprocessing Summary

* Missing values in the Age column were filled using the median age.
* Missing values in the Embarked column were filled using the most frequent category.
* The Cabin column was removed due to a large number of missing values.
* Categorical variables were encoded into numerical form.
* Numerical features were normalized using Min-Max Scaling.
* The cleaned dataset was saved for further analysis.

## Key Findings

### 1. Gender Strongly Influenced Survival

Female passengers had a significantly higher survival rate than male passengers. This suggests that gender played an important role during rescue operations.

### 2. Passenger Class Affected Survival Chances

Passengers traveling in first class were more likely to survive compared to passengers in second and third class. Higher-class passengers appeared to have better access to safety resources.

### 3. Higher Ticket Fare Was Associated with Better Survival

Passengers who paid higher fares generally showed better survival outcomes. This trend is closely related to passenger class and travel conditions.

### 4. Age Was Not the Sole Determining Factor

Although age showed some variation across survival groups, it was not the strongest predictor of survival when compared to gender and passenger class.

### 5. Survival Was Uneven Across Passenger Groups

The analysis showed clear differences in survival rates among different demographic and socioeconomic groups, indicating that survival was influenced by multiple factors rather than chance alone.

## Recommendations

* Passenger demographics should be considered when analyzing historical survival patterns.
* Multiple features should be examined together rather than relying on a single variable.
* Data preprocessing is essential for producing reliable analytical insights.

## Conclusion

The analysis revealed that gender, passenger class, and ticket fare were the most influential factors associated with passenger survival. Through data preprocessing and visualization, meaningful insights were extracted from the Titanic dataset, demonstrating the importance of data-driven decision making.
