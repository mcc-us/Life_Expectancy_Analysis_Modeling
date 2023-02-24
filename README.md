Life_Expectancy_Analysis_Modeling_Using_WHO_UN_Data

<p align="center">
  <img src="/assets/who-logo.png" width=120/><img src="/assets/blue-un-logo.png" width=90/>
</p>

---

LINK TO NB

This report investigates modifiable environmental factors that may contribute to life expectancy in the hopes of finding a mathematical model. Two questions are answered here: 

1. *Which variables are significant in modeling and predicting Life Expectancy?*

2. *What model best describes the relationship(s)?*


```
.
├── 10_MISC
│   ├── 1_Generate_clean_data_1.CSV_FROM_Life_Expectancy_Data.csv.ipynb
│   ├── 9_Produce_file_names_w_date_time_stamp.ipynb
│   └── traces_chat_gpt.ipynb
├── 3_EDA
│   ├── 3_Life_Expectancy_Exploratory_Data_Analysis.ipynb
│   ├── a_Life_Expectancy_Exploratory_Data_Analysis_PART2.ipynb
│   ├── LE_by_country_and_3D_Seaborn_Plots .ipynb
│   ├── NEED_LE_country_8regions.ipynb
│   ├── NEED_Violin_Plots.ipynb
│   ├── Seaborn_Graphics_Income_Education_age.ipynb
│   ├── Seaborn_Plots .ipynb
│   ├── WorkOnThis_Plotly_FACETING.ipynb
│   └── WorkOnThis_QQ Plots.ipynb
├── 3_Pandas_profiling_eda
│   ├── Life Expecteancy: IDA_EDA Report Using Pandas ProfilingBeta.html
│   └── Test_Pandas_Profiling_Report.ipynb
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
├── data
│   ├── processed
│   │   ├── clean_data_1.csv
│   │   ├── Clean_LE_Data_FEng_3.csv
│   │   ├── Clean_LE_Data_FEng_4.csv
│   │   ├── Clean_LE_Data_Post_Correlation_Testing.csv
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
├── jupy_notebook_notes
│   ├── Feature_table.ipynb
│   ├── Initial_Data_Analysis_notes.ipynb
│   └── Variable_table.ipynb
├── notebooks
│   ├── 1_MAIN_Life_Expectancy_WHO_UN_Analysis_Modeling.ipynb
│   ├── 2_Initial_Data_Analysis.ipynb
│   ├── Correlation_and_how_to_drop_highly_correlated_features.ipynb
│   ├── Plotly_Life_Expectancy_183_countries .ipynb
│   └── What exactly is missing from life expectancy data.ipynb
├── README.md
└── requirements.txt

16 directories, 93 files
```

