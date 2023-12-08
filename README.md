# Water Loss Analysis
This is a data analysis project that contributes to identification of critical influencing factors for the causes of pipe failures and leakage in water supply systems and utilizes Python for the analysis. The pipe network of the water supply system of city of Pforzheim, Germany, is used as a case study.
## Objective
The project objective is to increase the efficiency of the planning process for the rehabilitation of water supply systems as well as defining the risk of new pipe failures. The results of the analysis are expected to enable faster and more efficient identification of the factors causing pipe failures and leakage in water supply systems, and thus, to improve the current operational practice of the water utilities. 
## Key Questions
* The sales team needs to know what the busiest days of the week and hours of the
day are (i.e., the days and times with the most orders) in order to schedule ads at
times when there are fewer orders.
* They also want to know whether there are particular times of the day when people
spend the most money, as this might inform the type of products they advertise at
these times.
* Instacart has a lot of products with different price tags. Marketing and sales want to
use simpler price range groupings to help direct their efforts.
* Are there certain types of products that are more popular than others? The marketing
and sales teams want to know which departments have the highest frequency of
product orders.
* The marketing and sales teams are particularly interested in the different types of
customers in their system and how their ordering behaviors differ.
## Data
The dataset used in the analysis:

* orders
* products
* customers
* departments.
  
The full details of the data are available under [/data/.](https://github.com/SanjaIlinSpirovska/INSTACART-GROCERY_Python/tree/main/02%20Data/Original%20Data)
## Tools
For this project, the following python libraries were used:
+ pandas - for data analysis
+ NumPy - mathematical library that supports a variety of operations, a dependency of pandas
+ seaborn - for visualization
+ matplotlib - a plotting library and a dependency for seaborn
+ scipy - a fundamental Python library necessary for visualizations.
  
The code is available as jupyter notebooks, under [/scripts/](https://github.com/SanjaIlinSpirovska/INSTACART-GROCERY_Python/tree/main/03%20Scripts).
## Key Competencies
1. **Data Wrangling:** This involves tasks like dropping unnecessary columns, renaming columns for clarity, and adjusting variable data types. It ensures that the data is well-organized and suitable for analysis.
2. **Data Consistency Checks:** Identifying and rectifying mixed or incorrect data types, dealing with missing values and duplicates to maintain data quality and integrity.
3. **Merging Data:** Selecting and preparing data for merging, confirming the results of the merge using a merge flag, and exporting the data in Pickle format.
4. **Exploratory Analysis:** This phase involves exploring basic descriptive statistics for each variable, such as the range, quartiles, mean, and standard deviation.
5. **Deriving New Variables:** Creating new variables using if statements for-loops and the loc() function.
6. **Grouping Data & Aggregating Variables**
7. **Visualizing Data:** Utilizing data visualization libraries like Matplotlib and Seaborn to create various types of charts, including histograms, line charts, pie charts, and bar charts.
8. **Reporting Results:** Summarizing the findings in an Excel file. This report not only explains answers to questions from sales and marketing but also documents the data's journey, including population flow, consistency checks, data wrangling steps, and column derivations. It serves as a comprehensive documentation of the entire analysis process. 
