<<<<<<< HEAD
# Movie Studio Analysis
**Box Office Mojo and Rotten Tomatoes**
The analysis focuses on  importing data, inspection, and checking missing values using **Python and pandas**
=======
#
Movie Studio Analysis
**Box Office Mojo and Rotten Tomatoes*
The analysis focuses on  importing data,inspection and checking missing values using **python and pandas**
>>>>>>> Data_Cleaning

## datasets Used
## 1. Box Office Mojo
Provides revenue data for movies.
  - Domestic_Gross
  - Foreign_Gross
  - Total_Gross(sum of Domestic_Gross & Foreign_Gross)

## 2. Rotten Tomatoes
Provides movie ratings and review metrics

#Data Cleaning Steps
##Handle Missing Values
+Removed rows with missing revenue values in Box Office Mojo
+Drop rows with missing values in Rotten Tomatoes
+Drop rows with missing value in Box Office Mojo

##Remove Duplicates
+Dropped duplicate movie entries to avoid biased analysis
+Removed duplicate id in Rotten Tomatoes to improve data accuracy
+Removed duplicate title in Box Office Mojo to avoid double counting in our analysis

##Clean and Convert Data Types
+Removed $ and commas from revenue columns and converted them to numeric values.

##Final Clean Columns
###Box Office Mojo
+title
+studio
+Domestic_gross
+Foreign_gross
+year

###Rotten Tomatoes
+id
+review
+rating
+fresh
+critic
+top_critic
+publisher
+date