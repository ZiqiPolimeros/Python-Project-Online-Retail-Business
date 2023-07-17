<br>

<br>

<h1><span style="color:blue">Python Project: An Online Retail Business</span></h1>

<h5> 
Ziqi Polimeros<br>

NYC Data Science Academy<br>

Mentor: Stella Kim,  Ariella Brown, <br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Oren Ross, Sam Audino <br>

3/8/2022
</h5>
<br>

!['ecommerce'](https://github.com/ZiqiPolimeros/Python-Project-Online-Retail-Business/blob/main/pictures/Revenue vs. Return.png?raw=true)



<h2><span style="color:blue">Introduction: Growth of E-commerce</span></h2>  


E-commerce has kept growing and became a new channel to support businesses development. It has helped large retailers expand their customer base by selling online and given small businesses a chance to sell directly to customers on their own sites or through a platform like Amazon’s.  As a result, jobs created for e-commerce have grown 334% since 2002[1]. E-commerce has become the preferred way for many more people to shop. Particularly after COVID,  when many stores were closed or people wished to avoid going out among other shoppers,  the convenience of delivery to the home became necessary. 


![ecommerce](https://github.com/ZiqiPolimeros/Python-Project-Online-Retail-Business/blob/8193b0933a16e46a0a6ef880411e4c72eb9a12e8/pictures/growth.jpg?raw=true)

[2]

<h2><span style="color:blue">Data Source</span></h2> 

This is an international e-commerce online store. The owner also has businesses that buy in bulk and sell to other customers through retail outlet channels.
Information about the online shop business sales transactions:
- Business model: B2B & B2C
- Location: London
- Year established: 2007
- Date of the dataset: 12.2018 - 12.2019
- Size of the dataset: 500 thousand rows and 8 columns



<h2><span style="color:blue">Data Analysis</span></h2>

#### Analysis:  Overview

#### Discussion 1:
- We only performed the analysis from December 2018 to November 2019, because there were only ten days records in December 2019.
- The total sales revenue was about 64 million pounds sterling with over two million pounds sterling total return. 
- The total volume of business was over five million products with about 3800 product IDs.
- The company served about 4700 customers in 38 countries.


<br>

#### Analysis:  Monthly Sales 

!["sales"](https://github.com/ZiqiPolimeros/Python-Project-Online-Retail-Business/blob/main/pictures/1_sales.png?raw=true)

#### Discussion 2: 
- According to the monthly sales graph, over 90% of sales revenue was from Europe.
- The sales revenue increased from December 2018 to August 2019 and grew rapidly after September. The revenue from November was more than double the amount of the lowest sales month (2019/2).


<br>

#### Analysis:  Customers

!["sales"](https://github.com/ZiqiPolimeros/Python-Project-Online-Retail-Business/blob/main/pictures/5_customer.png?raw=true)

#### Discussion 3:
- Most of the top 20 buyers were from the United Kingdom. The biggest buyer, however,  was in the Netherlands and spent over 2 million pounds sterling.
- There were about 100 customers who only purchased once, and the one-time customers rate was 2.20%.


<br>

#### Analysis: Products

!["sales"](https://github.com/ZiqiPolimeros/Python-Project-Online-Retail-Business/blob/main/pictures/2_product.png?raw=true)

<br>

!["sales"](https://github.com/ZiqiPolimeros/Python-Project-Online-Retail-Business/blob/main/pictures/3_product.png?raw=true)

#### Discussion 4:
- The most popular product was "popcorn holder" with total sales of over 0.5 million pounds sterling.
- The product return rate was 3.48%. The top 20 return products were mostly from the United Kingdom.


<br>

!["sales"](https://github.com/ZiqiPolimeros/Python-Project-Online-Retail-Business/blob/main/pictures/4_product.png?raw=true)

#### Discussion 5:
- We made a correlation heatmap of the top 60 selling products. It shows that the absolute value of correlation coefficient of the great majority of the 60 products were smaller than 0.5. From the graph, we can say that very few products were accessories. They were mostly stand-alone products.
- The two pairs of products that have correlation:<br>
 The correlation of "Asstd Design 3d Paper Stickers" and "Mini Paint Set Vintage" is  0.604839<br>
 The correlation of "Small Chinese Style Scissor"  and " Lunch Bag Vintage Doily" is 0.545964 <br>
They both have a moderate relationship with each other.[3]

<br>

<h2><span style="color:blue">Suggestions </span></h2>

- The one-time purchase customer rate was 2.2% which means that the repeat customer rate was 97.8%. A repeat customer rate that is viewed as successful is between 20% to 40%[4]. We suggest that the company can invest more in marketing to expand the customer base.
- The product return rate of the year was 3.48%,  which is considered a low return rate as compared to the average return rate 10.6%[5]. However, the largest refund was over 0.8 million pounds sterling that was made up of almost 67% total return.  We can check the product’s quality, webpage demonstration and sale process to find out what needs to be improved. 
- Based on the heatmap graph, we can tell that most of the popular products were not related to each other. We suggest that the company offer some sales promotions or recommendations for product pairings (Customers who bought this also bought that) to increase the quantities of product sales. 


<br>

<h2><span style="color:blue">References </span></h2>

[1] "How the Growth of E-Commerce Is Shifting Retail Jobs". The New Nork Times.July 6 2017. <br>
[2] "E-commerce growth has hit a two-year high". Insider. August 17 2016. <br>
     https://www.businessinsider.com/e-commerce-growth-has-hit-a-two-year-high-2016-8 <br>
[3] "What is Considered to Be a “Strong” Correlation?".  Statology<br>
https://www.statology.org/what-is-a-strong-correlation/

[4] "Repeat Customer Rate". Geckoboard.com. <br>
     https://www.geckoboard.com/best-practice/kpi-examples/percent-returning-customers <br>
[5] Repko Melissa. "A more than $761 billion dilemma: Retailers’ returns jump as online sales grow". CNBC. January 25 2022. <br>
     https://www.cnbc.com/2022/01/25/retailers-average-return-rate-jumps-to-16point6percent-as-online-sales-grow-.html  

    
Dataset source： https://www.kaggle.com/gabrielramos87/an-online-shop-business

<br>

<br>
