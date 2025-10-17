# Python-Global-Superstore-Analysis
This is an analysis of retail data
# GlobalSuperStore Analysis Project

## Project Overview

**Project Title**: GlobalSuperStore Analysis  
**Level**: Beginner  
**Dataframe**: Dataframe which is denoted as df in this project

This project is designed to demonstrate python skills and techniques typically used by data analysts to explore, clean, and analyze retail sales data. The project involves setting up a superstore sales dataframe, performing exploratory data analysis (EDA). 


## Objectives

1. **Set up a dataframe**: Create and populate a sales dataframe with the provided sales data.
2. **Data Cleaning**: Identify and remove any records with missing or null values.
3. **Exploratory Data Analysis (EDA)**: Perform basic exploratory data analysis to understand the dataset.


## Project Structure

### 1. Dataframe Setup

- **Dataframe Creation**: The project starts by creating a dataframe.
- **Table Creation**: The dataframe is created by importing the pandas library,in order for us to use the read_csv method to read the data into python.


### 2. Data Preprocessing & Cleaning

	
	Data Preprocessing

- **Record Count**: Determine the total number of records in the dataset.
- **Ship Mode Count**: Find out how many unique shipping modes are in the dataset.
- **Customerid Count**: Identify all unique customerid's in the dataset.
- **Null Value Check**: Check for any null values in the dataset and delete records with missing data.
- **Duplicate Value Check**: Check for any duplicate values in the dataset and delete records with duplicate data.
- **Segment Count**:Find out how many unique segments are in the dataset.
- **City Count**:Find out how many unique cities are in the dataset.
- **State Count**:Find out how many unique states are in the dataset.
- **Countries Count**:Find out how many unique countries are in the dataset.
- **Regions Count**:Find out how many unique regions are in the dataset.
- **Categories Count**:Find out how many unique Categories are in the dataset.
- **SubCategories Count**:Find out how many unique SubCategories are in the dataset.
- **Productname Count**:Find out how many unique products are in the dataset.
- **Order priority Count**:Find out how many unique order priority are in the dataset.


	Data Cleaning
		
- **Create proper date format**:apply the to_datetime method to create proper dates.
- **Convert data types from string to numerical**:apply the astype method to create numerical datatypes.
- **Check numerical columns for negative values**:Sales column checked for negative columns.
- **Reduce dataframe size**:Drop unnecessary columns





### 3. Data Analysis & Findings

The data anlysis is performed in jupyter notebook and i invite you to scrutinise the analysis over there.

## Findings

- **State/City Analysis**:Sales have increased in each of the operating years.The last four Months of 4 months of the year are typically the busiest period. The exception is June where Sales spike,but then fall the following month.The sales have increased by 16,29 and 25% since inception. There was a slight decrease from 2013 to 2014 of 4%. But overall it has been generally significant growth. The month to month changes are very volatile,if we observe June 2013, we can notice the previous month had growth of 60% and June also had a 60% growth only for July sales to decrease by 46%,this is an alarming trend. We also observe that the first 2 months are usually the worst when it comes to sales. Sales Quantities have increased in each of the operating years. Sales Quantities vary substantially according to absolute values from month to month. Sales Quantities have increased in each of the operating years. The 2014 26% increment is the same as the previous period which is still encouraging but alarming, because it has not exceeded the previous year,which might require further investigation. Sales Quantities are very strong in November we can observe that the last 3 years we have enjoyed 40% increments,with only 2014 where there was a decrease to 31% which is also alarming. We also observe that August is a very outstanding Month for quantities sold as these range between 50 and 70%. In actual fact August seems to be our busiest period in terms of Sales Quantities. Most sales are shipped via standard class. Sales quantities also reflect the same as above. Standard class bears the most cost. Leading country by sales value is the USA, New York state and New York city being the leader by sales value. In Australia, the state of New South Wales is the leading state and city being Sydney. Leading country by sales volume is the USA, New York state and New York city being the leader. In second is the Philippines, the state of National Capital is the leading state and city being Manila. Asia Pacific is the leading market in terms of sales value. Asia Pacific also leads by sales volume. Leading region by far is the Central region by sales value. The Central region also leads by sales volume. The central region also leads by freight cost. When we include countries we observe that the Eastern region of the USA,which is New York is the leading region. Technology is the leading category by sales value. Office supplies are leading by sales volume. Technology is the leader by freight cost. In furniture sales chairs are the leading subcategory,In office supplies the top seller is storage and finally in Technology the Phones are the leading sub category by sales value. Overall the phones are leading by sales value. In furniture sales of chairs are the leading subcategory,In office supplies the top seller are Binders and finally in Technology the Phones are the leading sub category by sales volume. Overall the Binders are leading by sales volume.



## Conclusion

This project serves as a introduction to python for data analysis, covering dataframe setup, data cleaning, and exploratory data analysis.



## Author - analysethatdata

This project is part of my portfolio, showcasing the python skills essential for data analysis. 
