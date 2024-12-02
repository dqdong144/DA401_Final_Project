This folder contains data, jupiter notebook, R Markdown and related documents for Early Result. 
List of Documents: 
 1. DA401 Project.Rproj: R Markdown Project 
 2. Reading_Data.ipynb: Jupiter Notebook used to change the data format from DAT file in DAT_DAT folder to CSV_DATA/RawData
 3. Regression.Rmd: R Markdown to Perform regression Model
 4. Data.ipynb: Clean Data and perform Descriptive Analytics
 5. DAT_DATA: Raw Data folder: college_grads_2017.zip, college_grads_2019.zip, college_grads_2021.zip: NSCG raw data in 2017, 2019 and 2021
 6. CSV_DATA: This is where the csv data will be produced when running Reading_Data.ipynb. There are two folder: RawData (data after transform from DAT file), CleanData (data after clean and ready for regression) 

How to repoduce the results: 
  1. Unzip the Zip File to reproduce the data  
  2. Run eading_Data.ipynb to extract the data to csv data
  3. Run Data.ipynb: to clean the data and run EDA
  4. Run Regression.Rmd to run the regression models 
