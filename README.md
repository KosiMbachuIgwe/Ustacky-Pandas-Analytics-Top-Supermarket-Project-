# Ustacky-Pandas-Analytics-Top-Supermarket-Project-

Company XYZ owns a supermarket chain across the country. Each major branch located in 3 cities across the country recorded sales information for 3 months, to help the company understand sales trends and determine its growth, as the rise of supermarkets competition is seen to increase.

The data folder contains datasets from three different branches; Lagos, Abuja and Port Harcourt. Each data file from the branches contains the same attribute information and see below the attribute description.
Data analysis were performed from the data retrieved from all three branches of the top supermarket in Nigeria.

# Project Steps

In the course of the analysis, the following steps were taken:
1. Firstly, I loaded the dataset of the 3 branches together, combined into one file and converted to a csv file.

2. Secondly, libraries needed for analysis was imported. Statistical summary was explored from different branches to get more insight and there was no misssing value in the dataset. Current data type of the colums were checked using the info() method.

3. The date and time columns were observed, extracted and converted to datetime. The nunique() attribute  was also initiated to attain the count and sales.

4. Furthermore, a list of cathegorical column was explored using the unique() method.

5. The aggregation and groupby type categorizatio on the data was perpertrated.

6. Finally, I obtained different plotting methods using the seaborn visualzation library, matplotlib included to achieve results.

# Insights 

## Null Values:
The data collated properly had no missing values:

## Average() Function:
The approximate average unit price and quantity are #20,000 and 6 units respectively making our total sales/revenue to be around #120,000 without incurring tax. Note: The tax on the supermarket is about 4.5% of the total sales. After accounting for tax the average total value is found to be around #116,000. Knowing that the average cost of goods sold is approximately #110,700 and the gross income is approximately #5,537 it informs us that the average sales made within the timeframe are about #115,000

The average rating is 6.97 indicating that the supermarket is doing slightly better above-average implying that more work needs to be done to improve the companies services and products available to customers

All the data are filled with inputs and hence there are no null or empty data cells in the columns

We can say that Port Harcourt has the highest total gross income with Abuja being the second and then Lagos.


The branch/city  with the highest average rating is branch C(Port Harcourt) with branch A(Lagos) being the next in line followed by branch B(Abuja).

A large percent of the electrical accessories were paid for using the cash channel.

For home and lifestyle product lines it was majorly purchased using Epay.

There is a fine distribution of the payment channels used for the food and beverages product line.

Sports and travel have the majority of their products paid in cash.

Most of the customers who purchase health and beauty products were paid with using Epay.

A very large amount of the Fashion accessories were paid for using Epay.

Food And Beverages are sold most in Port-Harcourt.

Fashion accessories are also sold most in Port-Harcourt.

Lagos has the highest purchase for electronic equipment.

Sports and travel products were mostly sold in Abuja.

Home and lifestyle commodities are heavily purchased in Lagos.

Abuja and Port Harcourt have an approximately equal number of sales for health and beauty commodities.

The supermarket should focus on increasing its marketing strategy for sales of health and beauty products especially in Lagos which has a high potential yield rate.

In other for the Branch at Port-Harcourt to do better the sales management should work on generating more incoming through sports and travel, home and lifestyle commodities.

More efforts need to be put into the Lagos fashion accessory fraction.

Relative to Lagos and Port Harcourt, Abuja branch hasn't been doing well sales-wise as regards the yield in sales for the food, beverage, home, lifestyle. Hence, more attention should be given to these areas.

This indicates that there is a high variance in the correlation between the cost of goods sold and the total amount generated.

Dominant male activity in branch A and B while the females seem to be slightly higher than the males at Branch C.

# Future Work
In order to make my work more sturdy, the following tasks should have been carried out: 

a) Exploration of more data visualization tools.

b) Collection and addition of more relevant features.

c) Explore more financial columns for a much more economic descriptive analytics.

d) Use of more analytical approach to make a sustainable inference. 


# Standout Section 

a) Groupby Categorization of the areas with the most rating. Also, the interaction of unit price on the quantity of goods purchased.

b) Distribution visualization of sales by gender to see the volume of the total amount contributed by respective gender.

c) Comparison of other features to an important column 'RATING' which was not given in the project requirement. It is crucial to know the reaction of the branches to respective products and services provided, rating based on the product line.

# Executive Summary.

In this project, we were able to perform descriptive analysis using various pandas functions that help us analyze data including the Numpy, Matplotlib, Seaborn etc. Going through the data above, you could see there are other ways the task could be explored and accomplished on pandas. This is one good factor about using pandas because it aided insight to understand and determine company growth. 
