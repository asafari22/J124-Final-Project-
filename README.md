# J124-Final-Project: Data Analysis and Visualization of Housing Affordability for First Time Buyers in California 
### By Aryanna Safari 
-------------------------------------------------------------------------------------------------------------------
## Story Summary







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
 #### As shown,the region of SF BAY has the highest monthly payment including taxes and insurnaces with an average of $5,673.
 
 ![Q1 Pivot table C](https://github.com/asafari22/J124-Final-Project-/blob/c2dad5840e53b540dbbb4cd5d19862546a78598c/Q1%20-%20Pivot%20table%20B%20.png)
 
 To find the region with the lowest monthly payment including taxes and insurances, follow the above steps from 1 to 3.
 #### As shown, the region of Farth North has the lowest monthly payment including taxes and insurnaces with an average of $1,507.
 
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

![Q3 Pivot table C](









#### _Question #4: Looking at the data, which region or county has the most expensive homes that require the highest earning income? Which region or county has the lowest?_
#### Step-by-step answer:




#### _Question #5: Which county in the S.F Bay Area holds the highest median income? Which county holds the lowest?_
#### Step-by-step answer:




#### _Question 6#: Which region or county has the highest minimum qualifying income to purchase a home?Which county has the lowest?_
#### Step-by-step answer:
















---------------------------------------------------------------------------------------------------------------------------------------










## Data Visualization 






