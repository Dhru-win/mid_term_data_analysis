# Mid-Term Project (Analysis of Sales Product Data)

## Project/Goals

Our main goal for this project is to apply our learnings in Python & Tableau to analyze Sales Product data for a retail company, gain insight on current & future performance and provide recommendations. Our deliverables include the following:

1. Identify top performing and underperforming products/services.

2. Predict sales of a product in the next year.

3. Forecast future sales performance / potential revenue.

4. Identify demographics of customers and how it impacts sales.



## Process


### Step 1

Data Import.

* Merge all 12 .csv files into one. 

* Import file into Python. 

### Step 2

Data Pre-processing & EDA (Merging, Cleaning, Formatting)

* Combining datasets.

* Check for duplicates in order id.

* Detect outliers in price and quantity if any.

* Check for nulls and replace them with appropriate values.

* Convert order date to appropriate data type and get appropriate value.


### Step 3

Visualization & Insights

* Identify most selling items.

* Identify items that generate highest revenue.

* Calculate  mean, median, standard deviation, variance in appropriate fields.

* See if there are any specific date throughout the month and time through the day when sales are high.



### Step 4

Hypotheses testing.

* Our null hypothesis H0 is that price affects the quantity of products ordered: the lower the "Price", the higher the "Quantity Ordered".

* Performed correlation analysis between "Price Each" & "Quantity Ordered" weak and relationship is inverse.

* Checked for normality of the variables "Price Each" & "Quantity Ordered".

### Step 5

Dashborad Design & Conclusion.


## Results

* The highest selling product is AAA Batteries (4-Pack).

* The least selling products are LG washing machine and LG dryer. 

* Macbook Pro Laptop generates the highest revenue. 

* The highest selling product does not generate the highest amount of revenue.

* Highest sales recorded occurred in December 2019, probably end-of-year sales. 

* The variables "Price Each" and "Quantity Ordered" shows weak correlation and are also not normally distributed, hence the null hypothesis is rejected.




## Challenges 

* Data loading and cleaning.

* Integrating results obtained from different tools.

* Time constraints 



## Future Goals

* To continue to track the data base for more information as it updates.