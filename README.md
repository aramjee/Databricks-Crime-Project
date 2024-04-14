# Databricks-Crime-Project

### About the Project

######
+ This project uses Chicago crime data to predict the likehood of an arrest on certain categorical and numerical fields such as the district, time of day, and type of crime
+ The datasource is over 22 columns and +7.9 million rows: https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present
+ Data was extracted and stored in an Amazon S3 bucket and preprocessed to address any data integrity issues (duplicates, nulls, data type conversions)
+ For the purposes of running the ML tests (Decision Tree Classifier, XGBoost, Naiive Bayes, & Random Forest), the dataset was limited to recent years 2011-2022
+ Three different sample sizes were uses when running the test s in DataBricks premium on a seperate cluster of nodes (up to 4 nodes were used)

### PDF of Project Result
+ [Chicago Crimes Analysis.pdf](https://github.com/aramjee/Databricks-Crime-Project/files/14899403/Chicago.Crimes.Analysis.pdf)
  
### Databricks Notebook
+ https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3623708202541795/487412892863449/2377989951854267/latest.html
  
![image](https://github.com/aramjee/Databricks-Crime-Project/assets/26206720/21ffc90e-7af5-4ac6-b0b1-51a2a6f2842f)

![image](https://github.com/aramjee/Databricks-Crime-Project/assets/26206720/c6c4dda4-c179-44f5-9753-a23f7dee05f2)

![image](https://github.com/aramjee/Databricks-Crime-Project/assets/26206720/d4fa1f0d-e206-40f4-8eec-9949c0243e98)

![image](https://github.com/aramjee/Databricks-Crime-Project/assets/26206720/ae760590-c0c3-43d4-8050-71504aca1a04)







