# Customer Personality Analysis🤡🤓😱

- Kaggle dataset link: https://www.kaggle.com/imakash3011/customer-personality-analysis
--------------------------------------
## Context 📜:
- **Problem Statement** 🚨:
Customer Personality Analysis is a detailed analysis of a company’s ideal customers. It helps a business to better understand its customers and makes it easier for them to modify products according to the specific needs, behaviors and concerns of different types of customers.
Customer personality analysis helps a business to modify its product based on its target customers from different types of customer segments. For example, instead of spending money to market a new product to every customer in the company’s database, a company can analyze which customer segment is most likely to buy the product and then market the product only on that particular segment.

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/Blog_Banner_v1-01-1024x410.jpg' width='600px' ></img>
----------------------------------
## Content 📃:
**Attributes**

- ID: Customer's unique identifier
- Year_Birth: Customer's birth year
- Education: Customer's education level
- Marital_Status: Customer's marital status
- Income: Customer's yearly household income
- Kidhome: Number of children in customer's household
- Teenhome: Number of teenagers in customer's household
- Dt_Customer: Date of customer's enrollment with the company
- Recency: Number of days since customer's last purchase
- Complain: 1 if customer complained in the last 2 years, 0 otherwise
Products
------------------------------------------------------------------
- MntWines: Amount spent on wine in last 2 years
- MntFruits: Amount spent on fruits in last 2 years
- MntMeatProducts: Amount spent on meat in last 2 years
- MntFishProducts: Amount spent on fish in last 2 years
- MntSweetProducts: Amount spent on sweets in last 2 years
- MntGoldProds: Amount spent on gold in last 2 years
Promotion
------------------------------------------------------------
- NumDealsPurchases: Number of purchases made with a discount
- AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
- AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
- AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
- AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
- AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
- Response: 1 if customer accepted the offer in the last campaign, 0 otherwise
Place
----------------------------------------------------------------------------
- NumWebPurchases: Number of purchases made through the company’s web site
- NumCatalogPurchases: Number of purchases made using a catalogue
- NumStorePurchases: Number of purchases made directly in stores
- NumWebVisitsMonth: Number of visits to company’s web site in the last month

-------------------------------------------------------------------------
## Target🎯:
**Need to perform clustering to summarize customer segments.**
The most important part of a customer personality analysis is getting the answers to questions such as:
1. What people say about your product: what gives customers’ attitude towards the product.
2. What people do: which reveals what people are doing rather than what they are saying about your product.

In the section below, I’ll walk you through a data science project on analyzing customer personality with python. Here I will be using a dataset that contains data collected from a marketing campaign, where our task is to predict how different customer segments will respond for a particular product or service.

----------------------------------------------------------------------
## Approach🪧:
- Firstly I collected dataset from *Kaggle* and imported with help of **Pandas**, analayzed data and figured out number of columns and rows also there were how many null values in every column. Most of the columns are binay i.e 0 & 1 so I plotted count graph for every binary attribute column.
Filled the null values by mean of that column. Performed *Exploratory Data Analysis*, *Data Visualization* by **Matplotlib**, **Seaborn** and **Plotly**. Merged some columns into one which contains simillar properties and dropped non-useful columns in the dataset. As the problem is to find types of personaliy of customers so **Clustering** is the finest way to do this task.
- Technically this is a **Machine Learning** problem and for clustering **K-Means** is the perfect choice. To find perfect number of customers, I used **Silhoutte Method**.
- After finding number of clusters in the dataset I visualized thoses cluster(types of customers) with many other attributes of the dataset and made a report at the end of the notebook.
- Saved clean and well organize data from two different stages and made two Tableau dashboards.
------------------------------------------------------------------------------------------
## Visuals📈📊:
- Visuals from **Plotly** are not visible on GitHub, so here are those visuals.

**Plotly** Visuals from notebook

Line[39]:

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/newplot.png' height=300px, width=350px></img>

Line[40]:

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/newplot2.png' height=300px, width=350px></img>

Line[41]:

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/newplot3.png' height=300px, width=350px></img>

Line[42]:

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/newplot4.png' height=300px, width=350px></img>

Line[43]:

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/newplot5.png' height=300px, width=350px></img>

Line[44]:

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/newplot6.png' height=300px, width=350px></img>

Line[45]:

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/newplot7.png' height=300px, width=350px></img>

Line[46]:

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/newplot8.png' height=300px, width=350px></img>

Line[47]:

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/newplot9).png' height=300px, width=350px></img>

--------------------------------------------------------------------------------------------------------------------------------------------------
## Tableau Dashboards:

Dashboard 1:
(by **data_visuals.csv**)

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/Dashboard1.png'></img>

Dashboard 2:
(by **data_visuals2.csv**)

<img src='https://github.com/karan842/Data-Science-Projects/blob/master/Customer%20Personality%20Analysis/Images/Dashboard2.png'></img>

-----------------------------------------------------------------------------------------------------------------
## Thank You⭐
