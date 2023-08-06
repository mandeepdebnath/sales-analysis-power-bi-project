Sales Analysis Insights using Power BI
======================================

Tools used: Power BI, Power Query, DAX

Steps followed:
---------------

1.  Cleaning the data

2.  Transforming the data

3.  Designing data model

4.  Creating calculated columns

5.  Creating measures

6.  Designing visuals

A sales analysis has been built after performing the above steps with the dataset of around 5000 rows of data containing valuable information regarding the business.

After cleaning and transforming the data using Power Query, I created the data model to establish relationships between different tables in the data which is very important to get accurate insight.

![Data Model](https://lh5.googleusercontent.com/eewbq359nmgviM6dtOLf8jF2ZXN-dqQgoBl-6XZ1RKxuWjfv1JcvQW9slZ3FTkHKX4SbO6M6gKB5GZ1dMJfHWn_KWTkBxUrNbqU1RW8MkLfaR2cgWQ-ZjB8tnvbYSGhK_zj9BtDRKnvRNVkh3Tvz6Cg)

After the data model was created I created some calculated columns and measures to answer the business questions, which are shown below:

1\. Total Sales
---------------

![Total Sales](https://lh3.googleusercontent.com/BHy1QtmUObKgSoe1s8OYPtaWcK_uAqBYz5ZbJXkV4K8sJwwVSu-BVEHtjYSw-cghWiNhRYiAvxjh6XjMx-jFAilTSiWV2zQSPLB80dOESXFSvKXr7x2El-fMpjoVTmKNR611bM6aHV3Pg2sWUytTboU)

Displaying the total sales value for the selected period, allows users to understand the overall revenue generated in the years 2017 to 2019.

2\. Total Profit
----------------

![Total Profit](https://lh5.googleusercontent.com/d1OS7lP9I8CV8KXLFg1uXC58qaAvVrdBgXgBbxO1hShYdRwQdD6JEj-Yz9nEgLl3mFv_eEW4ESTFkZoD2Yw_Vp5mkE4YlLIPl_QM5Vnmy6O2mRAFMaDq7JRTslSRIP4dXFe8KEUH8x0YO4WB2h5B9I8)

Visualizing the total profit achieved based on the sales data, providing insights into the financial performance.

3\. Total Profit Margin
-----------------------

![Total Profit Margin](https://lh5.googleusercontent.com/6Lg8lk7MaeILbGV3SOyVe9TcnaZAumx3OFdUgVdjuaRENA79aFNZkp4zyOvtJr2oA-GR1jeIpAZtn5Hxk1vUuU_zHpUd3rR-CuCJCy5cuyQbw3F8QpG7TBe5GKA37UB8Owo25jRBUDG30XpKsJRreUs)

Visualizing the profit margin percentage which will enable users to assess the profitability of products.

4\. Analyzing Orders by Product and Comparing with the Previous Year
--------------------------------------------------------------------

![Products](https://lh5.googleusercontent.com/OUzQT3GlqlC5ykNXjdE7u_8yHrSThA7ZBvO0U8Xjtl5zpqP2AYsaNQ6vIMhn53M8OnxTTn9GXd1xdMLnwCX-atZ8L6W72dJhMEVeN4g7hpDlzH9jm8V04WJwB71PrMj-5usFEPmATqw2i3xFWcvA1B0)

Analyzing the number of orders placed during the selected period, helping to identify sales patterns and order trends. The black line shows the sales generated up to the previous year, this gives insight on how much the sales have increased in the current year.

Also, it shows us our most selling product in the market which is "Product 7" in the year 20117 to 2019.

5\. Sales by Month Comparing  with the Previous Year
----------------------------------------------------

![Sales by Month](https://lh5.googleusercontent.com/nZ7W59treZERgCfc5BVFwrPsoD6D8tgsvqgYkwkCSukj84_O71Fhm421f6O7HG0G3d9j0pfkYxqKv9DwRJTWDmiHJHVhoU1yeHgTTuoVenqFI4rUlNWvmdo_k3S9QPhhbk7ALEGCi-9KLKnafc7RjLI)

Sales performance across different months between the selected period and the previous year, identifying regions with significant changes. The black line denotes the sale of the previous year.

The red columns denote that the sale of the current month of the current year in less than that of the same month the previous year, which tells us the sales of that particular month has declined. This is an important measure that will help us identify the problems that have caused this decline and take decisions accordingly.

6\. Top 5 Cities
----------------

![Top Cities](https://lh5.googleusercontent.com/PCmMUssg2I-SDHBGg0yHT41KDmCPSaEBgl8mXc--fc-_7wZCfCKw9DjOeSvDY-3e5sIgusCMProUWvI1TFhwAzvNP1sBmBH0BAxpeRySkPh5nHy9q1T1JwB64VK0HFOXPAL0TLNo9rtZGwAMG2JNP4k)

Showcasing the top 5 cities based on sales, allows us to quickly identify the most lucrative locations.

7\. Profit by Channel
---------------------

![Profit by Channel](https://lh5.googleusercontent.com/X38_8kFSc_UyLr590DmS2-o98GgQK7Wy4FJbEhzZ8jb1IL7txoxAw-PBNUC8hjcxvIV3YG9PMOil8nDblBbTtJr25IEqp56jw3qcBR_MSVl88i_pRC8lZ6LiuFTiMIvsBZxCKsytyyqeQw4f1u9P34I)

Comparing the profit generated by each channel between the selected period and the previous year, indicating improvements or challenges in profitability.

8\. Sales by Customer and Compare with Previous Year
----------------------------------------------------

![Sales by Customer](https://lh5.googleusercontent.com/8g8Q2gdKOR9lAHi3T7oi1XAN3-a6af14Mtk7lHTpoCRFUZe1YAAicu21iLWeRAvHqxY4ahsB02x2A4dIopWkyuz0p-OUQ6M5UizJdRAe1c1WG9dZ1POXQ6KnAzOJ2Y8ORKPMhLw-GRYoEQJVXYrjdsE)

Analyze sales data by customer, highlighting the performance of individual customers and comparing it to the previous year.

Final Steps
-----------

Creating Slicers for Date, City, Product, and Channel. This will enable us to interact with the data by selecting specific dates, cities, products, and channels, allowing for dynamic filtering and personalized analysis.

Adding Tooltip to view the insights like total sales, total profit, and top 5 cities for a particular product, channel, or customer when we hover over that particular column.

![Tooltip](https://lh6.googleusercontent.com/1QJOHpDg5q14T0ckQapeNvEs4GqrdrzIHlHFR58XpDPbHxvW1bPJxjZZr9KNNJiEOoQFsB6v2WHXfgP8p2Pq2fAtwPAinsC9vjpczql7s8BEKUFLscLdJZrUXDP1RjcEfPiUUrSzJqmPTFTn5vX8y9Y)

Final Dashboard
---------------

![](https://lh3.googleusercontent.com/frFNcpeYCjqwBGb1cEPfpUcWSgCXiMkwV-wMcr9mLMdjP1IBXfQxl0njeGL6EvAhFlG3j3mhRiZApcuG7MH2l9yrE_-iky6Nthn5xj4D0kpSaw6jNmkLLc-MeNNmRQ0mpryWsEyc1jHU6wHEekhWaRI)
------------
So, this is the end of the project explanation. Do connect with me on [Linkedin](https://www.linkedin.com/in/mandeepdebnath/)
