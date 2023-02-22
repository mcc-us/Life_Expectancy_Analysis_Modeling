Life_Expectancy_Analysis_Modeling_Using_WHO_UN_Data

<center>

  | ![WHO](/assets/blue-un-logo.png) | ![UN](/assets/who-logo.png) |
  |:--------------------------------:|:---------------------------:|
  |        World Health Organization |              United Nations |

</center>

---

**Problem Statement**

This report investigates modifiable environmental factors that may contribute to life expectancy in the hopes of finding a mathematical model. Two questions are answered here: 

1. *Which variables are significant in modeling and predicting Life Expectancy?*

2. *What model best describes the relationship(s)?*

**File Structure**
```
.
├── backup
│   ├── 1_MAIN_Life_Expectancy_WHO_UN_Analysis_Modeling.ipynb
│   ├── 2_Life_Expectancy_Initial_Data_Analysis.ipynb
│   ├── 3_Life_Expectancy_EDA.ipynb
│   ├── 4_Life_Expectancy_Exploratory_Data_Analysis_PART2.ipynb
│   ├── 7_Life_Expectancy_Modeling.ipynb
│   ├── 8-Life_Expectancy_Linear_Coefficients.ipynb
│   ├── 9-Life_Expectancy_Groupings.ipynb
│   └── Clean_LE_Data_w_Means_2.csv
├── categorize_plots
│   ├── Excellent_eda.ipynb
│   ├── EXCELLENT_What Exactly is Missing from Life Expectancy data.ipynb
│   ├── Good_Seaborn_Plots .ipynb
│   ├── LE_by_Countrfy_BMI Vs Rate Change of BMI.ipynb
│   ├── Life Expectancy Vs Yearly Age Rate.ipynb
│   ├── Plotly_FACETING.ipynb
│   ├── QQ Plots.ipynb
│   ├── Seaborn_Graphics_Income_Education_age.ipynb
│   └── traces_chat_gpt.ipynb
├── Clean
│   ├── 1_Life_Expectancy_WHO_UN_Analysis_Modeling_MAIN.ipynb
│   ├── 2_Life_Expectancy_Initial_Data_Analysis.ipynb
│   ├── 3_Life_Expectancy_EDA.ipynb
│   ├── 4_Life_Expectancy_Exploratory_Data_Analysis_PART2.ipynb
│   ├── 5_Life_Expectancy_Recursive_Feature_Elimination.ipynb
│   ├── 6_Life_Expectancy_Modeling.ipynb
│   ├── 6_Modeling_NOTES.ipynb
│   └── Untitled.ipynb
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
│       └── WHO_life_expectncy_data.zip
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
│   ├── Life Expecteancy WHO UN Data: EDA Report Using Pandas Profiling.html
│   ├── REport_Section.odt
│   ├── Test Pandas Profiling Report: All Features.html
│   └── Test_Pandas_Profiling_Report.pdf
├── figures
│   ├── age_avs_yearly_age_rate.png
│   ├── Life_Expectancy_Educagtion_BMI.svg
│   ├── Life_Expectancy_vs_8_Regions.svg
│   ├── Screenshot at 2023-02-01 10-12-34.png
│   └── test_age_avs_yearly_age_rate.png
├── misc
│   ├── 1_Generate_clean_data_1.CSV_FROM_Life_Expectancy_Data.csv.ipynb
│   ├── 1_WHO_Life_Expectancy_IDA_EDA beta.ipynb
│   ├── 4_Feature_Engineering-Copy1.ipynb
│   ├── 5_Recursive_Feature_Elimination-Copy1.ipynb
│   ├── 9_Categorize Countries Into Regions.ipynb
│   ├── 9_Produce_file_names_w_date_time_stamp.ipynb
│   ├── Countrt_Feature_Rates.ipynb
│   ├── IDA w REORDER cols-Changed Config.Yml.ipynb
│   ├── IDA w REORDER cols.ipynb
│   ├── Linear Model 1 - WHO L.E..ipynb
│   ├── Linear Model Only.ipynb
│   ├── Recursive Feature Elimination.ipynb
│   ├── test statsmodel api.ipynb
│   ├── updated-2016-data-tables_preventing_disease_deaths_dalys_pafs_sept_2019_rev.xlsx
│   └── Who_Notebook_No2_EDA.ipynb
├── notebooks
│   ├── 1_MAIN_Life_Expectancy_WHO_UN_Analysis_Modeling.ipynb
│   ├── 2_Life_Expectancy_Initial_Data_Analysis.ipynb
│   ├── 3_Life_Expectancy_EDA.ipynb
│   ├── 4_Life_Expectancy_Exploratory_Data_Analysis_PART2.ipynb
│   ├── 6_Life_Expectancy_Recursive_Feature_Elimination.ipynb
│   ├── 7_Life_Expectancy_Modeling.ipynb
│   ├── 8-Life_Expectancy_Linear_Coefficients.ipynb
│   ├── 9-Life_Expectancy_Groupings.ipynb
│   ├── Excellent_5_Life_Expectancy_Feature_Engineering.ipynb
│   └── LE_EDA_Violin_Plots.ipynb
├── notes
│   ├── config_default.yaml
│   ├── default_ON.yaml
│   ├── hover-text-and-formatting.py
│   ├── le_yr_prog.txt
│   ├── Make Yr Own DF.ipynb
│   ├── mcc_config.yaml
│   ├── missing_vars
│   ├── notes
│   ├── notes2
│   └── preventing_disease_through_healthy_environments_who.pdf
├── Pandas_profiling_eda
│   ├── CLEAN_Life_Expecteancy_Pandas_Profiling_Reporting.html
│   ├── Life Expecteancy: IDA_EDA Report Using Pandas ProfilingBeta.html
│   ├── Life Expecteancy: IDA_EDA Report Using Pandas Profiling.html
│   ├── output.html
│   ├── report.html
│   ├── Test_Pandas_Profiling_Report.ipynb
│   ├── WHO Life Expecteancy: IDA_EDA_Report.html
│   ├── WHO_Life_Expecteancy_Pandas_Profiling_Reporting.html
│   ├── WHO_RE_ORDER_NEW_CONFIG_YML_Profiling_Reporting.html
│   └── WHO_RE_ORDER_Pandas_Profiling_Reporting.html
├── README.md
├── requirements.txt
└── Unification2
    ├── 1_MAIN_Life_Expectancy_WHO_UN_Analysis_Modeling.ipynb
    ├── 3_Life_Expectancy_EDA.ipynb
    ├── 4_Life_Expectancy_EDA_PART2.ipynb
    ├── 5_Life_Expectancy_Feature_Engineering.ipynb
    ├── 6_Life_Expectancy_Recursive_Feature_Elimination.ipynb
    ├── 7_Life_Expectancy_Modeling.ipynb
    ├── 8-Life_Expectancy_Linear_Coefficients.ipynb
    ├── 9-Life_Expectancy_Groupings.ipynb
    └── AOK2_Life_Expectancy_IDA.ipynb

13 directories, 118 files
```
