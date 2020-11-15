### Forage Data Analyst Virtual Experience

# [Quantium Data Analytics Virtual Experience Program](https://www.theforage.com/virtual-internships/NkaC7knWtjSbi6aYv)

- This program consists of 3 modules.

Task 1: Data preparation and customer analytics

Task 2: Experimentation and uplift testing

Task 3: Analytics and commercial application


---

### Code and Resources Used
**Python Version:** 3.7\
**Packages:** pandas, numpy, matplotlib, datetime

Data Cleaning:

Date column was in integer format that was changed to datetime data type.
We needed to ensure that we were only dealing with products that were chips. After splitting the product name into words we figured out there were salsa products that needed to be removed. 
Found an outlier in "PROD_QTY" column. The customer only bought once a year in bulk(qty 200) suggesting this was for a commercial purpose. The customer was removed from the analysis.
The first word in "PROD_NAME" was value counted to find the different ways a product can be expressed. A new column was created called "Cleaned_Brand_Names".
