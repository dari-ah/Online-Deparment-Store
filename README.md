# Deparment Sale Analysis
  In this project, I analyzed the sales record of an online department store's sales for 2021. I designed my data based on an [e-commerce dataset](https://www.kaggle.com/datasets/venkatkrishnan/ecommerce-sales-data) I found on Kaggle. Since the store has many categories, from clothing to electronics, I wanted to see how each category performed. Furthermore, I wanted to examine if the sellers were making profits.
  
 ### Table of Contents
* [Objective](#objective)
* [Dataset](#dataset)
* [Results](#results)

## Objective: 
  In this online department store, the products are sold by many independent sellers. My goal was to determine the top sellers and buyers and which products they were interested in. I wanted to analyze which categories and products were best-selling. I also wanted to find products that were worst-selling or not being sold at all. Moreover, I aimed to analyze the revenues of each seller and determine how well they performed on the platform. 

## The Dataset:
  The original dataset contains information about the products, prices, and the seller IDs. Since I wanted to analyze how the sellers and buyers contributed to the sales and their interaction with the platform, I separated the data into three tables, following the [data schema](https://github.com/dari-ah/Online-Deparment-Store/blob/e40ebee6ef313071276d9cce78d9e9944bce4f6c/Data%20Schema-Purchase.pdf) attached. The first table stored the information about when the buyers made an account. I used Buyer_ID as the primary key. The second table stores information about the purchases that were being made. I generated unique Purchase_IDs to use as the primary key for the table. Lastly, the third table stores information about the products and sellers. 

## Results:
   From my queries, the majority of the best-selling products were 24% in the Home Decor Festive Needs categories and 16% in the Automotive categories. These products were purchased twice in 2021. For worst-selling products, 36% of the products were in the Clothing categories, 12% in Jewelry categories, and the rest were spread out in the other 17 categories. These products were not being purchased at all in 2021. Despite being 35% of the worst-selling products, Clothing made up 12% of best-selling products and ranked first as the top-selling category. The worst-selling categories for 2021 were Health Personal Care Appliances and Food Nutrition. Each of the categories had one purchased time each. There was no category in which buyers did not purchase.
   
  In 2021, the total revenue was $5,801,829. The number of sellers who could not make any sales during the year was 58, which was 2.35% of the total number of sellers. On the other hand, the best seller could make up to $1,036,907, which was 18% of the total revenue. 
  
 [View my visualization](https://public.tableau.com/app/profile/anh1535/viz/OnlineDepartmentSaleAnalysis2021/Dashboard1)
  
Compared to the average sales for department stores, this online store was under-performed. However, most buyers could make sales and earn a lot of profit in this department store.

