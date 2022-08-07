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










#### _Question #3: Which region or county has the highest minimum qualifying income to purchase a home?Which county has the lowest?_
#### Step-by-step answer:





#### _Question #4: Looking at the data, which region or county has the most expensive homes that require the highest earning income? Which region or county has the lowest?_
#### Step-by-step answer:




#### _Question #5: Which county in the S.F Bay Area holds the highest median income? Which county holds the lowest?_
#### Step-by-step answer:




#### _Question 6#: Which counties or regions have a minimum qualifying income over $100,000?_
#### Step-by-step answer:
















---------------------------------------------------------------------------------------------------------------------------------------










## Data Visualization 






