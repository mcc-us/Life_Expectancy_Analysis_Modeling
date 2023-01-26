Title: Life_Expectancy_WHO_UN_Analysis_Modeling

To:    Magnimind

From:  Matt Curcio

Date:  2023-01-24

Re:    Python Data Analysis Project # 3

---

**Problem Statement**

This report investigates modifiable environmental factors that may contribute to life expectancy in the hopes of finding a mathematical model. The primary questions we answer are:

1. *Which variables are significant and important in modeling and predicting Life Expectancy?*
2. *What steps should be taken given limited resources?*

**Data Analysis Overview**

1. Initial Data Analysis
2. Exploratory Data Analysis
3. Feature Engineering
4. Recursive Feature Elimination
5. Modeling

**Introduction**

In 2006, The World Health Organization published a report entitled `Preventing disease through healthy environments`.
>[It] “confirms that approximately one-quarter of the global disease burden, and more than one-third of the burden among children, is due to modifiable environmental factors.” 
>
>[WHO-Preventing Disease Through Healthy Environments](https://www.who.int/publications/i/item/9241593822)

Information from the World Health Organization and United Nations was gathered for the years 2000-2015 for 183 countries in three categories: 

1. *Communicable diseases*: Hepatitis B, Measles, Polio, Diphtheria, HIV/AIDS.

2. *Country-specific monetary data*: Gross domestic product, Governmental expenditure rates, Average personal income, Developmental status, Population, Education.

3. *Health-related information*: Infant and adult mortality rates, Number of deaths less than 5 yr, Alcohol consumption rates, Child-related malnutrition, including child thinness rates between 1-19 years and 5-9 years, Average body mass index per capita.


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
