# TechSpark_Analysis
  
  <p align="center">
  <img width="300" alt="Screenshot 2025-02-14 at 8 50 36 PM" src="https://github.com/user-attachments/assets/fc2f27c9-0f43-4f0a-9466-700940c945cd" />
</p>
  

TechSpark, founded in 2018, quickly established itself as a go-to online retailer for consumer electronics, offering a curated selection of popular devices and accessories from leading brands like Apple, Samsung, and Lenovo.  Catering to a tech-savvy audience, TechSpark provides high-quality portable audio solutions and powerful computing devices. Since its inception, TechSpark has prioritized offering a seamless online shopping experience, competitive pricing, and reliable delivery, contributing to its steady growth and reputation within the competitive e-commerce landscape. As the business scales, TechSpark continues to strive for excellence in delivering cutting-edge products and customer satisfaction.

## Company Background



<details>
  <summary>Project Goals</summary>
<br /> 
Since 2019, Techspark has collected data on various parts of their business including, orders, customers, products, and regional data. Although this data is not cleaned, it presents challenges but also unique opportunities to provide valuable insights to drive key business decisions.   
  
<br /> 
<br /> 
As we clean this data, our goal is to think about how can we support the various departments including finance, sales, product and marketing with real world actionable insights and also increase our market share on the global scale. 

</details>

<details>
  <summary>Stakeholder Questions</summary>
<br /> 
1. What were the overall sales trends from 2019 to 2022? <br /> 
2. What were the company's yearly and monthly growth rates? <br /> 
3. How has the new loyalty program performed? Should we keep using it? <br /> 
4. What was the company's refund rate and average order value (AOV)? <br /> 
<br /> 

**Notes:**
- Focus on sales revenue, AOV, and order counts
- Look at trends over yearly and monthly periods 
- For refunds and AOV specifically compare across Apple products
</details>

<details open>
  <summary>Table of Contents</summary>

- [Executive Summary](#executive-summary)
- [Insights Deep Dive](#insights-deep-dive)
    - [Sales Trends](#sales-trends)
    - [Product Trends](#product-trends)
    - [Geographical Trends](#geographical-trends)
    - [Loyalty Program](#loyalty-program)
    - [Refund Rates](#refund-rates)
      - [Spotlight: Apple Products](#spotlight-apple-products)
- [Recommendations](#recommendations)
</details>

# Executive Summary

![Screenshot 2025-02-20 at 3 07 26 PM](https://github.com/user-attachments/assets/d6ec0c48-1e4e-4506-866a-b3dd2b9d4317)

Throughout 2019-2022, we see that monthly revenue spike closer to the end of 2020 and then slowly declined. Monthly sales peaked around $1.25 million and declined in the later years to lower than what it initally was to only $260k sales. Similarly, number of orders peaked in 2021 with around 35k orders and then slowly declined to only 21.5k orders in 2022 representing a 45% annual decline in total order count. 

### ERD
<img width="881" alt="Screenshot 2025-01-31 at 10 15 27 AM" src="https://github.com/user-attachments/assets/cd07751f-5f4f-4e39-86d9-6e2d7f0cfd04" />


# Insights Deep Dive



## Sales Trends

talk about how sales changed over the 2019-2022

What were the monthly and yearly number of sales throughout 2019 and 2022? What about AOV and total sales in dollars?

Thoughout 2019 to 2022 E-list sold over 108k orders totaling $28.1 Million. The average monthly sales throughout this time period were 585k. The month with the highest total sales were September 2021 while the month with lowest total sales occurred on October 2022. The average order value for all months within this time period was $252.94. The Month with the highest average order value (AOV) was $321.62 which occurred in October 2021 and the month with the lowest AOV was $216.32 which was in October 2022. The average order count per month for this time period was 2,253. The month with the most amount of orders were December 2020 with 4,019 orders while the month with the least amount of orders were in October 2022 with only 825 total orders. 

When we look into the data by year, we see that 2020 by far had the most with $10.1 million total sales 2021 took the lead when it came to order count at 35,858 orders although total sales was about $1 million less than in 2020. 2020 also had the highest AOV with the average order value being $300.16.  Overall total sales peaked in 2020 and then started declining the years following with the largest decline happening in 2022. 


Which months and products performed the best / worst? Is there seasonality?

When we look at months combined we can see some cyclicality when during the month of October and February with a huge decline in growth rates -28% and -25% respectively. The best months were December, November and March with growth rates of 22.97%, 18.49% and 18.30% respectively.  Apple products accounted for a little more than half of all sales. Gaming monitors accounted for the largest amount of sales for a single product with 35% of total sales. 

## Product Trends
talk about the increase/decrease in sales for specific products over 2019-2022
How did this differ by product and geography?

North America accounted for more than half of the total sales throughout 2019-2022 in addition to the highest order count with 55,805 orders. 
APAC had the highest average order value the average order being $278.81 but only accounted for 13% of total sales. 

## Geographical Trends
talk about increase/decrease from different regions 

How did this differ by product and geography?

North America accounted for more than half of the total sales throughout 2019-2022 in addition to the highest order count with 55,805 orders. 
APAC had the highest average order value the average order being $278.81 but only accounted for 13% of total sales. 

## Loyalty Program
Should we keep using the loyalty program?

What was the monthly number of sales and AOV for people in the loyalty program vs. those not in the loyalty program? How does this trend differ for recent months vs. previous months?

Initially when the loyalty program began, Non loyalty sales dominated significantly however in the more recent years, 2021 and 2022 shows that total sales of loyalty members surpassed that of non loyalty members. Additionally, average order value in the most recent years have also shown improvement with 2022 loyalty members having almost a $30 lead in average order value with $214 for non loyalty members and $244 for loyalty members. With this uptrend, I would reccomend continuing the loyalty program to see if the trend continues with positive growth. 

## Refund Rates
What are the refund rates for Apple products?

Refund rate for all apple product throughout this time period were 5.9%.
What are the refund rates for each of the Apple products? How does this differ by year?

Refund rate for all apple product throughout this time period were 5.9%. As we break this down by specific apple products we see that MacBook Air laptops were returned most frequently with 11.9% returns, followed by apple iPhones at 7.9% and lastly apple headphones with a return rate of 5.4%. When we look at returns over the year, we see that even though MacBook laptops had the most amount of returns we can see the trend shows that MacBook Air laptop returns are decreasing over the years.  it is worth noting that returns for all products in 2022 were 0%. This it extremely unusual and would be something we would need to look into with the help of the data engineering team to be sure that the data is being pulled in correctly. Note: 3 orders did not have a categorized date so this was excluded from our analysis. This accounts for <1% of our data. 

