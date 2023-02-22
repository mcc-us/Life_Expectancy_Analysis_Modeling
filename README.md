Life_Expectancy_Analysis_Modeling_Using_WHO_UN_Data

<p align="center">
  <img src="/assets/who-logo.png" width=120/><img src="/assets/blue-un-logo.png" width=90/>
</p>

---

LINK TO NB

**Problem Statement**

This report investigates modifiable environmental factors that may contribute to life expectancy in the hopes of finding a mathematical model. Two questions are answered here: 

1. *Which variables are significant in modeling and predicting Life Expectancy?*

2. *What model best describes the relationship(s)?*


```
.
├── 10_MISC
│   ├── 1_Generate_clean_data_1.CSV_FROM_Life_Expectancy_Data.csv.ipynb
│   ├── 9_Produce_file_names_w_date_time_stamp.ipynb
│   └── traces_chat_gpt.ipynb
├── 1_main
│   ├── 1_Life_Expectancy_WHO_UN_Analysis_Modeling_MAIN.ipynb
│   ├── 1_MAIN_Life_Expectancy_WHO_UN_Analysis_Modeling.ipynb
│   └── 1MAIN_Life_Expectancy_WHO_UN_Analysis_Modeling.ipynb
├── 2_IDA
│   ├── 1_WHO_Life_Expectancy_IDA_EDA beta.ipynb
│   ├── AOK2_Life_Expectancy_IDA.ipynb
│   ├── Excellent_2_Initial_Data_Analysis.ipynb
│   ├── IDA w REORDER cols-Changed Config.Yml.ipynb
│   └── IDA w REORDER cols.ipynb
├── 3_EDA
│   ├── 3_Life_Expectancy_EDA_beta.ipynb
│   ├── 3_Life_Expectancy_EDA.ipynb
│   ├── 4_Life_Expectancy_EDA_PART2_beta.ipynb
│   ├── 4_Life_Expectancy_Exploratory_Data_Analysis_PART2.ipynb
│   ├── Excellent_2_Initial_Data_Analysis.ipynb
│   ├── Excellent_eda.ipynb
│   ├── EXCELLENT_What Exactly is Missing from Life Expectancy data.ipynb
│   ├── LE_EDA_Violin_Plots.ipynb
│   ├── Plotly_FACETING.ipynb
│   ├── QQ Plots.ipynb
│   └── Who_Notebook_No2_EDA.ipynb
├── 3_Pandas_profiling_eda
│   ├── Life Expecteancy: IDA_EDA Report Using Pandas ProfilingBeta.html
│   └── Test_Pandas_Profiling_Report.ipynb
├── 4_Graphics
│   ├── Good_Seaborn_Plots .ipynb
│   └── Seaborn_Graphics_Income_Education_age.ipynb
├── 5_Feature_ENG
│   ├── 4_Feature_Engineering-Copy1.ipynb
│   ├── 5_Life_Expectancy_Feature_Engineering.ipynb
│   └── Excellent_5_Life_Expectancy_Feature_Engineering.ipynb
├── 6_Recursive_Feat_Elim
│   ├── 5_Recursive_Feature_Elimination-Copy1.ipynb
│   ├── 6_Life_Expectancy_Recursive_Feature_Elimination_beta.ipynb
│   ├── 6_Life_Expectancy_Recursive_Feature_Elimination.ipynb
│   └── Recursive Feature Elimination.ipynb
├── 7_Models
│   ├── 7_Life_Expectancy_Modeling_beta.ipynb
│   ├── 7_Life_Expectancy_Modeling.ipynb
│   ├── 8-Life_Expectancy_Linear_Coefficients_beta.ipynb
│   ├── 8-Life_Expectancy_Linear_Coefficients.ipynb
│   ├── Linear Model 1 - WHO L.E..ipynb
│   ├── Linear Model Only.ipynb
│   └── test statsmodel api.ipynb
├── 8_Groupings
│   ├── 9_Categorize Countries Into Regions.ipynb
│   ├── 9-Life_Expectancy_Groupings_beta.ipynb
│   └── 9-Life_Expectancy_Groupings.ipynb
├── 9_RATE_Changes
│   ├── Countrt_Feature_Rates.ipynb
│   ├── LE_by_Countrfy_BMI Vs Rate Change of BMI.ipynb
│   └── Life Expectancy Vs Yearly Age Rate.ipynb
├── assets
│   ├── age_avs_yearly_age_rate.png
│   ├── blue-un-logo.png
│   ├── Life_Expectancy_Educagtion_BMI.svg
│   ├── Life_Expectancy_vs_8_Regions.svg
│   ├── notes
│   │   ├── config_default.yaml
│   │   ├── default_ON.yaml
│   │   ├── hover-text-and-formatting.py
│   │   ├── le_yr_prog.txt
│   │   ├── Make Yr Own DF.ipynb
│   │   ├── mcc_config.yaml
│   │   ├── missing_vars
│   │   ├── notes
│   │   ├── notes2
│   │   └── preventing_disease_through_healthy_environments_who.pdf
│   ├── Screenshot at 2023-02-01 10-12-34.png
│   ├── test_age_avs_yearly_age_rate.png
│   └── who-logo.png
├── categorize_plots
│   └── Good_Seaborn_Plots .ipynb
├── data
│   ├── processed
│   │   ├── clean_data_1.csv
│   │   ├── Clean_LE_Data_FEng_3.csv
│   │   ├── Clean_LE_Data_FEng_4.csv
│   │   ├── Clean_LE_Data_Post_EDA_2.csv
│   │   ├── Clean_LE_Data_Post_EDA_3.csv
│   │   ├── Clean_LE_Data_w_Means_1.csv
│   │   ├── Clean_LE_Data_w_Means_2.csv
│   │   ├── Life_Expectancy_Data.csv
│   │   ├── regional_data_2-2023-01-18 13:18:55.451573.csv
│   │   ├── regional_data_2.csv
│   │   ├── SUBSET_who_le_data.csv
│   │   ├── x_test.csv
│   │   ├── x_train.csv
│   │   ├── y_test.csv
│   │   └── y_train.csv
│   └── raw
│       ├── Life_Expectancy_Data.csv
│       └── Life_Expectancy_Data.zip
├── docs
│   ├── 1_MAIN_Life_Expectancy_WHO_UN_Analysis_Modeling_MAIN.pdf
│   ├── 2_Life_Expectancy_Initial_Data_Analysis.pdf
│   ├── 3_Life_Expectancy_EDA.pdf
│   ├── 4_Life_Expectancy_Exploratory_Data_Analysis_PART2.pdf
│   ├── 5_Life_Expectancy_Feature_Engineering.pdf
│   ├── 6_Life_Expectancy_Recursive_Feature_Elimination.pdf
│   ├── 7_Life_Expectancy_Modeling.pdf
│   ├── 8-Life_Expectancy_Linear_Coefficients.pdf
│   ├── forward.odt
│   ├── jan29.odp
│   ├── REport_Section.odt
│   ├── Test_Pandas_Profiling_Report.pdf
│   └── updated-2016-data-tables_preventing_disease_deaths_dalys_pafs_sept_2019_rev.xlsx
├── README.md
└── requirements.txt

18 directories, 97 files
```
