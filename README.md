
# [Quantium Data Analytics Virtual Experience Program](https://www.theforage.com/virtual-internships/NkaC7knWtjSbi6aYv)

- The program consists of 3 modules.

### Module 1: Data preparation and customer analytics. 
#### Conduct analysis on your client's transaction dataset and identify customer purchasing behaviours to generate insights and provide commercial recommendations.

#### Skills: Data Validation, Data Visualization, Data Wrangling and Programming.


### Module 2: Experimentation and uplift testing
#### Extend analysis from Module 1 to help identify benchmark stores that allow to test the impact of the trial store layouts on customer sales.

#### Skills: Data Analysis, Commercial thinking, Statistical Testing.


### Module 3: Analytics and commercial application
#### Use analytics and insights from Modules 1 and 2 to prepare a report for the client, the Category Manager.

#### Skills: Commercial thinking, Presentation skills, Communication Skills

---

### Code and Resources Used
**Python Version:** 3.7\
**Packages:** pandas, numpy, matplotlib, datetime

#### Data Cleaning:

* Date column was in integer format that was changed to datetime data type.
* We needed to ensure that we were only dealing with products that were chips. After splitting the product name into words we figured out there were salsa products that needed to be removed. 
* Found an outlier in "PROD_QTY" column. The customer only bought once a year in bulk(qty 200) suggesting this was for a commercial purpose. The customer was removed from the analysis.
* The first word in "PROD_NAME" was value counted to find the different ways a product can be expressed. A new column was created called "Cleaned_Brand_Names".

#### Analysing Customer Segments of Data:
* TOT_SALES column was grouped by to find the top 3 customer segments: 
* RETIREES                  14805
* OLDER SINGLES/COUPLES     14609
* YOUNG SINGLES/COUPLES     14441

