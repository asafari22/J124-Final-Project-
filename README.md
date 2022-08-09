# J124-Final-Project: Data Analysis and Visualization of Housing Affordability for First Time Buyers in California 
### By Aryanna Safari 
-------------------------------------------------------------------------------------------------------------------
## Story Summary

Housing is becoming more and more expensive. In California, one of the most desirable states in the US, the cost of buying a home for first time buyers can be extremely intimidating. This data breaks down how much you need to be making in each county/region correlated with the monthly payments including insurance, as well as the median qualifying income needed to purchase a home. To give a quick snap shot, the average cost of a home for first time buyers in the state of California as of 2022, costs on average $608,818. However, that is not affordable for the majority of Californian's looking to buy a home. The SF Bay Area is overall the most expensive area to purchase a home, which means you have to have a higher income. In fact, nearly 54% of home buyers in the SF Bay Area can afford a home over $608,818, however in Central Valley Region, only 3.91% of the first time home buyer population can afford a home. In fact, only 17 out of 52 counties in California hold an average income over $100,000 as first time home buyers. Affordable housing is rare and it is becoming more difficult for the younger generation to save for a home when the real estate market is skyrocketing. The analysis I have shared, provides a small glimpse of comparison in levels of affordabilty or lack thereof.


## Additional Sources:

1. For the first additional source, the California Association of Realtors, also has data on [Housing Affordability by Ethnicity in California](https://github.com/asafari22/J124-Final-Project-/blob/6d63fcdd35a70087e7826ffa134a2e91f332cad8/Affordability%20by%20Ethnicity%20-%202021.pptx). This would be a helpful tool to look into deeper and analyze the contrast within each region/county in comparison to the median cost to purchase a home in California. Comparing the ethnic diversity or lack thereof may be helpful for those looking to purchase a home. It is also interesting to look and see what communities are lacking diversity and why that is. Looking into what are the most affordable or least affordable, as well as median cost to purchase a home for each ethnic background.

2. For the second additional source, the California Association of Realtors, also has data on [Current Sales and Price Statistics](https://github.com/asafari22/J124-Final-Project-/blob/22adad3961065730ae9acc137823f45e17ccbc5d/County%20Sales%20&%20Price%20Statistics%20(Public).xlsx). Looking at this data and looking at the median sold price of the homes in 2022, specifically the median sold price of each region and the price change from month to month or year to year. This could be a helpful tool for first time home buyers to see the range in which homes are selling for in their area of interest and whether the market is up or down. This can prepare future home buyers so that they have enough information on requirements and how much money they may need if the price of the home goes up or down. 

-------------------------------------------------------------------------------------------------------------------------------------------------------
#### Potential Interview Contacts:

1. **Christine Dosen, at Coldwell Banker Best Realty** 
  * Email: christine.dosen@coldwellbankerrealestate.com
  * Phone Number:425-876-3405
  * As one of the top Real Estate Agents in California for numerous years, I believe she would be a great asset to have a conversation about the real estate market; what has changed in the past few years, different types of housing options, affordability, the direction of the market, etc.

2. **Alex Kane, at Coldwell Banker Best Realty**
 * Email: 	alex.kane@cbrealty.com
 * Phone Number: 949-837-5700
 * As a real estate agent in Orange County for numerous years, Kane could be great to speak to about demographics in Orange County since there is so many cities within it. Getting insight on age of first time home buyers, the average cost of homes in the area, if there is an incline or decline in popularity in the region and how it compares to other popular regions in the state. 


## Data Analysis Process 

###### To follow along with this dataset, you will need to download the [“First Time Buyer HAI”](https://car.sharefile.com/share/view/s92eba5817d7345419f8433254737f789) data sheet as a .csv file and then upload it to Google Sheets. 
##### _Next, the following five questions and a step-by-step for each answer:_

#### _Question #1: Which region requires the highest monthly payment including taxes and insurance? Which has the lowest?_
#### Step-by-step answer:

To find the region with the highest monthly payment including taxes and insurances:
  1. Create a pivot table and add 'Region' to **Rows** and 'Monthly Payment Incl.Taxes and Insurance' to **Value**.
  ![Q1 Pivot table](https://github.com/asafari22/J124-Final-Project-/blob/ecce057453521acf98f5bb945edee188555ba074/Q1%20Screen%20shot%20pivot%20table%20.png) 
 2. In **Rows**, sort the 'Region' by **'Avergage Monthly Payment Incl. Taxes and Insurance'** 
 3. In **Values**, summarize the 'Monthly Payment Incl. Taxes and Insurance' to **AVERAGE** 
 
 ![Q1 Pivot table B](https://github.com/asafari22/J124-Final-Project-/blob/fb43308d9cb452383a96c5ae4fdeb60ce5bf9aa3/Q1%20-%20Pivot%20table%20B%20.png)
 #### As shown,the region of SF BAY has the highest monthly payment including taxes and insurances with an average of $5,673.
 
 ![Q1 Pivot table C](https://github.com/asafari22/J124-Final-Project-/blob/c2dad5840e53b540dbbb4cd5d19862546a78598c/Q1%20-%20Pivot%20table%20B%20.png)
 
 To find the region with the lowest monthly payment including taxes and insurances, follow the above steps from 1 to 3.
 #### As shown, the region of Farth North has the lowest monthly payment including taxes and insurances with an average of $1,507.
 
 ![Q1 Pivot table D](https://github.com/asafari22/J124-Final-Project-/blob/639aa5c063f0c8f2d388b50d6b012868a7cccf0e/Q1-%20Pivot%20table%20D.png)
 
 
#### _Question #2: In each each region, what is the highest 'median home price' in that county? What is the lowest?_
#### Step-by-step answer:

To find the highest median home price in each county of that region:
  1. Create a pivot table: first add 'Region' and then 'County' to **Rows**. Add 'Median Home Price' to **Values**
  2. In order to find the most expensive county of that region with the corresponding median home price, change the 'Order' to 'Descending' and sort by 'AVERAGE of Median Home Price' for 'Region'. Follow the same steps for 'County'.
  3. In values, make sure that the 'Median Home Price' is summmarized by the 'AVERAGE'. 

![Q2 Pivot table A](https://github.com/asafari22/J124-Final-Project-/blob/639aa5c063f0c8f2d388b50d6b012868a7cccf0e/Q1-%20Pivot%20table%20D.png)

#### Next, looking through the data, it is clear what the highest median home price is in each county/region:
From the most expensive to least expensive region: **SF Bay**, **Central Coast**, **Southern California**, **Other**, **Central Valley**, and lastly **Far North.**

![Q2 pivot table B](https://github.com/asafari22/J124-Final-Project-/blob/fc6d98357bd5f4a46eca5ee17b39ddaeb89f9644/Q2%20pivot%20table%20B.png)
* In SF BAY, San Mateo is the most expensive county with an average median home price of **$1,865,750.**
* On the Central Coast, Santa Cruz is the most expexpensive county with an average median home price of **$1,156,992.**
* In Southern California, Orange is the most expensive county with an average median home price of **$1,865,750.**
* In Other, Mono is the most expensive county with an average median home price of **$881,880.**
* In Central Valley, San Benito is the most expensive county with an average median home price of **$720,380.**
* In Far North, Butte is the most expensive county with an average median home price of **$382,500.**

![Q2 pivot table C](https://github.com/asafari22/J124-Final-Project-/blob/8a7d8469fd4fa15e7c9384230b9fbfcf1dcc3c01/Q2%20pivot%20table%20C.png)

![Q2 pivot table D](https://github.com/asafari22/J124-Final-Project-/blob/56d898a24a2bdc3af1bd40548e08fd1a8f49f00f/Q2%20pivot%20table%20D.png)

**To find the lowest median home price in each county of that region, follow the similar steps for highest median home price:**
1. The pivot table will be the same: first add 'Region' and then 'County' to **Rows**. Add 'Median Home Price' to **Values**
2. In order to find the most expensive county of that region with the corresponding median home price, change the 'Order' to 'Ascending' and sort by 'AVERAGE of Median Home Price' for 'Region'. Then, follow the same steps for 'County'.
3.In values, make sure that the 'Median Home Price' is summmarized by the 'AVERAGE'. 

#### Since the pivot table elements are the same, just changing from descending order to ascending order to see what the lowest median home price is in each county/region:

![Q2 pivot table E](https://github.com/asafari22/J124-Final-Project-/blob/bcc88eac2e4e594022caf0bb0d96cec354772762/Q2%20pivot%20table%20E.png)

![Q2 pivot table F](https://github.com/asafari22/J124-Final-Project-/blob/9e3e9b77b155b2c626429119693c71b2bece1cc1/Q2%20pivot%20table%20F.png)

* In Far North, Lassen is the least expensive county with a median home price of **$208,250.**
* In Central Valley, Kings is the least expensive county with a median home price of **$276,250.**
* In Other, Lake is the least expensive county with a median home price of **$300,900.**
* In Southern California, San Bernardino is the least expensive county with a median home price of **$391,000.**
* On the Central Coast, San Luis Obispo is the least expensive county with a median home price of **$724,410.**
* In SF Bay, Solano is the least expensive county with a median home price of **$510,000.**


#### _Question #3: Which counties/regions have a minimum qualifying income over $100,000? Which county requires the higest qualifiying income?_
#### Step-by-step answer:

1. Create a pivot table: 
* 'Region' and 'County' to **Rows**. Order both in 'Ascending' order and sort by 'Average of Minimum Qualifiying Income' for both 'Region' and 'County'.
2.  Add the 'Minimum Qualifiying Income' to **Values** and summarize by 'AVERAGE'
3. Add the 'Minimum Qualifying Income' to **Filters** and change the status to 'Filtered by condition and values'
4.  Select **'Greater than'** and input 100,000 as the value.

![Q3 Pivot table A](https://github.com/asafari22/J124-Final-Project-/blob/0c18b944d697b7e2697eacf948759ded68048fbf/Q3%20-%20pivot%20table%20A.png)
![Q3 Pivot table B](https://github.com/asafari22/J124-Final-Project-/blob/01084b26d0cc4c8e2c8abbbaed1fcba8ad6fe8b8/Q3%20pivot%20table%20B.png)

Once those steps have been followed, it should appear as so:

![Q3 Pivot table C](https://github.com/asafari22/J124-Final-Project-/blob/01084b26d0cc4c8e2c8abbbaed1fcba8ad6fe8b8/Q3%20pivot%20table%20B.png)

**As shown, San Benito, Ventura, San Diego, Orange, Mono, San Luis Obispo, Monterey, Santa Barbara, Santa Cruz, Sonoma, Contra Costa, Napa, Alameda, Marin, San Francisco, Santa Clara, and San Mateo all have minimum qualifiying incomes over $100,000.**

To find the county/region that requires the highest qualifiying income, simply chanfge the order in 'Region' and 'County' to **'Descending'**
* Now it shows that the 'Region' of **SF Bay**, specifically, **San Mateo** county has the highest qualifying income of **$274,500.**

![Q3 pivot table D](https://github.com/asafari22/J124-Final-Project-/blob/3d7b36ec9fefcc71b490f8e7ccd16cd837b029e2/Q3%20pivot%20table%20D.png)
![Q3 pivot table E](https://github.com/asafari22/J124-Final-Project-/blob/e5f5019e666b841dd796da3e4625540680b17c95/Q3%20pivot%20table%20E.png)


#### _Question #4: What is the average qualifying income in the state of California? In which regions/counties can one afford a home with the average qualifying income?_
#### Step-by-step answer:

1. Create a pivot table:
 * Add 'Region' to **Rows**
 * Add 'Minimum Qualifying Income' to **Values**
 
 ![Q4 pivot table A](https://github.com/asafari22/J124-Final-Project-/blob/66a4daabaaf3593e3e7387d732399a4142b0c0e3/Q4%20pivot%20table%20A.png)
 
 **It is clear that the average minimum qualifying income for all of California is $89,656.**
 
 ![Q4 pivot table B](https://github.com/asafari22/J124-Final-Project-/blob/57a80b6f023f82cac03f628341866d486be54eea/Q4%20pivot%20table%20B.png)

**Next, in order to find out which regions/counties can afford a home with the average qualifying income of $89,656:**

#### Step-by-step answer:
1. Keep the same steps as above and add 'Minimum Qualifying Income' to **Filters** and change the status to **'Value is greater than or equal to'** and then enter **89,656.**
2. Add 'County' to **Rows**

![Q4 screen shot C](https://github.com/asafari22/J124-Final-Project-/blob/0da3d49587273edbfa8a15c463889c613383b5ce/Q4%20screen%20shot%20C.png)

**Next, in the pivot table, it is clear which regions/counties can afford a home with a qualifiying income greater than or equal to $89,656**

![Q4 screen shot D](https://github.com/asafari22/J124-Final-Project-/blob/0b5aac22f44fc14a07ee69c7134515574cdeb6ad/Q4%20screen%20shot%20D.png)

**Only within the regions of Central Coast, Central Valley, Other, SF Bay, and Southern California can one afford a home greater than or equal to the minimum qualifying income of $89,656 in the state of California.**
 * **Central Coast**: San Luis Obispo, Monterey, Santa Barbara, and Santa Cruz
 * **Central Valley**: San Benito
 * **SF BAY**: Sonoma, Contra Costa, Napa, Alameda, Marin, San Francisco, Santa Clara, and San Mateo
 * **Southern California**: Los Angeles, Ventura, San Diego, and Orange


#### _Question #5: What percentage of Californian's in each region can afford a home that is OVER the average cost as first time home buyers?_
#### Step-by-step answer:
  
  1. To calculate average of 'Median Home Price', simply select the entire column and use the **'filter'** element to find the average:

![Q5 screen shot A](https://github.com/asafari22/J124-Final-Project-/blob/713d55f037f8d7190775219db6d3e3c409fea502/Q5%20screenshot%20A.png)

It is clear that the median home price for first time buyers in California is **$608,818**.

#### Follow these steps to find out the percentage of Californian's in each region that can afford a home that is OVER the average cost for a first time home buyer at $608,818:
  1. Create a pivot table:
    * Insert 'Region' in **'Rows'** and order by 'Ascending'.
    * Insert 'Minimum Qualifying Income in **'Rows'** and order by 'Ascending' and sort by 'Minimum Qualifying Income'.
  2. In **'Values'**, insert 'Median Home Price' and summarize by 'SUM' and show as '% of column'
  3. In **'Filters'**, insert 'Median Home Price' and change the 'Status' to 'Filter by condition', then select ' Greater than or equal to' and enter the average cost for a first time home buyer in California: **608,818**

**It should look like this:**

![Q5 screen shot B](https://github.com/asafari22/J124-Final-Project-/blob/d4a935355944ed45a0df28d2b65cec5f5f4c8916/Q5%20screen%20shot%20B.png)
![Q5 screen shot C](https://github.com/asafari22/J124-Final-Project-/blob/21c760e9a962ca769b5f34b04f7b87c1942b86de/Q5%20screen%20shot%20C.png)

**Your chart will look like this:**

![Q5 screen shot D](https://github.com/asafari22/J124-Final-Project-/blob/c0c80b50b953266af227960d404384c8a2c0f714/Q5%20screen%20shot%20D.png)

**It is clear that:**
  * 3.91% of Central Valley region first time home buyers can afford a home over the average cost in California.
  * 4.79% of Other region first time home buyers can afford a home over the average cost in California.
  * 17.72% of Southern California region first time home buyers can afford a home over the average cost in California.
  * 19.81% of the Central Coast region first time home buyers can afford a home over the average cost in California.
  * 53.77% of the SF Bay region first time home buyers can afford a home over the average cost in California.


## Data Visualization 
----------------------------------------------------------------------------------------------------------------------------------------
The following is a map of the [Median Home Price Per Region for First Time Home Buyers in California](https://datawrapper.dwcdn.net/piHjx/1/)

![Data wrapper map](https://github.com/asafari22/J124-Final-Project-/blob/cc307d9bd43aea2502e0e751e941fdfa7978264a/Data%20Wrapper%20Map.png)

