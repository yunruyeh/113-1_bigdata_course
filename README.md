# 113-1_bigdata_course

This is our project in big data class. (And all the details are in the PDF files below.)

# Part 1 :
## Diabetes Management and AI in Insulin Delivery Systems
Authors: Yun Ju Yeh and Beatrice Pasini

This phase focused on loading, inspecting, and preparing raw datasets related to glycemia levels and treatments (insulin doses and carbohydrate intake). The team conducted the following key steps:

Data Standardization: Timestamps in both CSV and Excel files were standardized to datetime objects for alignment.

Exploratory Analysis: Data distributions and trends (e.g., glycemia variability and treatment frequencies) were visualized, revealing patterns of hyperglycemia and hypoglycemia.

Daily Filtering: Demonstrated how to isolate data from a specific day for targeted analysis.

Dataset Unification: Merged CGM (Continuous Glucose Monitoring) and treatment datasets by aligning timestamps and handling missing values.

Resampling: SGV (sensor glucose values) data were resampled into consistent 5-minute intervals. Missing values were interpolated.

Normalization and Visualization: Data were normalized (scaled between 0 and 1) and plotted to identify relationships between glycemia, insulin, and carbohydrates.

Initial Findings: Clear correlations were observed—especially the influence of insulin and carbohydrate intake on blood sugar levels.

[Diabetes Management and AI in insulin delivery System.pdf](https://github.com/user-attachments/files/20588050/Final.project.part.1.pdf)

# Part 2 :
## Enhancing AI Analytics in Health Care through Data Quality
Authors: Yun Ju Yeh and Beatrice Pasini

This stage focused on data cleaning, transformation, and feature engineering to prepare high-quality data for AI-driven health analytics. Key contributions include:

Advanced Data Processing: Parsed and cleaned timestamps; dropped missing and invalid values; merged datasets using merge_asof for precise temporal alignment.

Time-Series Structuring: SGV data were resampled at 5-minute intervals to synchronize with treatment records.

Absorption Modeling: Simulated gradual insulin and carbohydrate absorption over 5 hours using linear distribution logic.

Handling Missing/Erroneous Data: Replaced abnormal SGV (outside 40–400) with nulls, applied forward/backward filling, and used interpolation for insulin/carb data.

Feature Construction: Created derived columns such as insulin_basal, insulin_bolus_absorbed, and carbs_absorbed to support AI model training.

Final Validation: Ensured the final dataset was complete, logically consistent, and saved for downstream machine learning tasks.


[Enhancing AI analítics in Health care through data quality.pdf](https://github.com/user-attachments/files/20588049/Enhancing.AI.analitics.in.Health.care.through.data.quality.pdf)
