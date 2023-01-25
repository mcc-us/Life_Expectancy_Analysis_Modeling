Title: Life_Expectancy_WHO_UN_Analysis_Modeling

To:    Magnimind

From:  Matt Curcio

Date:  2023-01-24

Re:    Python Data Analysis Project # 3

**Problem Statement**

This report investigates modifiable environmental factors that may contribute to life expectancy in the hopes of finding a mathematical model. The primary questions we answer are:

1. *Which variables are significant and important in modeling and predicting Life Expectancy?*
2. *What steps should be taken given limited resources?*

**Data Analysis has 5 sections**

1. Initial Data Analysis: which deals with the 'cleaning' the data using imputation by mean.
2. Exploratory Data Analysis: An examination of the variables, histograms, percentile information, and other graphics that explore and explain the input and output.
3. Feature Engineering: Categorization of the 193 countries was discretized into eight groups.
4. Recursive Feature Elimination: 
5. Modeling: A linear regression model was examined.


Information from the World Health Organization and United Nations was gathered for the years 2000-2015 for 183 countries in three categories: 

1. *Communicable diseases*: Hepatitis B, Measles, Polio, Diphtheria, HIV/AIDS.

2. *Country-specific monetary data*: Gross domestic product, Governmental expenditure rates, Average personal income, Developmental status, Population, Education.

3. *Health-related information*: Infant and adult mortality rates, Number of deaths less than 5 yr, Alcohol consumption rates, Child-related malnutrition, including child thinness rates between 1-19 years and 5-9 years, Average body mass index per capita.


**File Structure**
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
│   ├── 4_Life_Expectancy_Feature_Engineering.ipynb
│   ├── 5_Life_Expectancy_Recursive_Feature_Elimination.ipynb
│   ├── 6_Life_Expectancy_Modeling.ipynb
│   └── 6_Modeling.ipynb
├── README.md
├── references
├── reports
│   ├── config_default.yaml
│   └── Life Expecteancy: IDA_EDA Report Using Pandas Profiling.html
└── requirements.txt

7 directories, 20 files
