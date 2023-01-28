Title: Life_Expectancy_WHO_UN_Analysis_Modeling

To:    [Magnimind](https://magnimindacademy.com/)

From:  Matt Curcio

Date:  2023-01-29

Re:    Python Data Analysis & Modeling Project # 3

---

**Problem Statement**

This analysis investigates modifiable environmental factors that may correlate with life expectancy in the hopes of finding a mathematical model. The primary questions we answer are:

1. *Which variables are significant and important in modeling and predicting Life Expectancy?*


2. *What model best describes the relationship(s)?*


**Synopsis of Results**

Seven predictors have the most importance in this model. 

They include: ['Income', 'Education', 'HIV', 'DTP', 'Polio', 'lt5yD', 'AdultMort']

Four algorythms were tested accuracy alone was used as a benchmark:

| Model | Average % Accuracy (cv=5) |
|:------|--------------------------:|
| Gradient Boosting Regressor | 94.7 |
| Decision Tree Regressor     | 88.5 |
| Linear Regression         | 81.0 |
| Support Vector Regressor  | 19.0 |


**File Structure**
```
.
├── data
│   ├── processed
│   │   ├── Clean_LE_Data_FEng_4.csv
│   │   ├── Clean_LE_Data_Post_EDA_3.csv
│   │   ├── Clean_LE_Data_w_Means_2.csv
│   │   ├── x_test.csv
│   │   ├── x_train.csv
│   │   ├── y_test.csv
│   │   └── y_train.csv
│   └── raw
│       └── Life_Expectancy_Data.csv
├── docs
├── notebooks
│   ├── 1_MAIN_Life_Expectancy_WHO_UN_Analysis_Modeling_MAIN.ipynb
│   ├── 2_Life_Expectancy_Initial_Data_Analysis.ipynb
│   ├── 3_Life_Expectancy_EDA.ipynb
│   ├── 4_Life_Expectancy_Exploratory_Data_Analysis_PART2
│   ├── 5_Life_Expectancy_Feature_Engineering.ipynb
│   ├── 6_Life_Expectancy_Recursive_Feature_Elimination.ipynb
│   ├── 7_Life_Expectancy_Modeling.ipynb
│   ├── 7_Modeling_NOTES.ipynb
│   └── 7_Modeling.ipynb
├── README.md
├── references
├── reports
│   ├── config_default.yaml
│   └── Life Expecteancy: IDA_EDA Report Using Pandas Profiling.html
└── requirements.txt
```
7 directories, 20 files
