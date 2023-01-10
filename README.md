# Airbnb-Booking-Analysis-EDA

![image](https://user-images.githubusercontent.com/57758182/211594412-e7bc3a5c-bb94-490c-91c4-787a34f2cee2.png)


Airbnb has been an American Company since 2008, it is an online marketplace that connects people who want to rent out their homes with people who are looking for accommodations in specific locations.

The dataset which is used for the analysis is from AirBnb based in NewYork. NewYork is amongst the most expensive cities in the world where the cost of living and the tariff for staying in the hotels or apartments are very high.

The objective of the project is to perform an exploratory data analysis, data pre-processing, data cleaning & imputation, and in the end, apply different Data Visualization techniques to get meaningful insights from the given data.

Explore and analyze the data to discover key understandings like.

  ● What can we learn about different hosts and areas?
  
  ● What can we learn from predictions? (ex: locations, prices, reviews, etc)
  
  ● Which hosts are the busiest and why?
  
  ● Is there any noticeable difference in traffic among different areas and what could be the reason for it?
  
  ● What is average revenue per host and how does it vary for different neighbourhood groups.
  
  ● Depict the price distribution among neighbourhood groups.
  
In order to answer these questions, various feature analysis, comparison are performed and proper conclusions are drawn. Features of the dataset being location with coordinates, prices, hostname, room types, availability throughout the year, number of reviews, etc. Carried-out feature engineering, data cleaning that included identifying and handling the null values, of certain features and checked for correlation between features.

Descriptive analysis is done to show skewness of the features. Talking about host with most listings, most reviews and most earnings include the analysis on
feature-"host". Next we have explored the neighbourhood groups with most listings and its geographical distribution.

Explored on various relations to learn from predictions of:

● Variation of average price across the neighbourhood groups for all room types.

● Reviews per neighbourhood groups.

● Describing the distribution of price among neighbourhoods.

● Describing the distribution of reviews among neighbourhoods.

● Analysed the busiest host based on neighbourhoods with most listings, number of listings of each room type and most number of reviews. And obtained the following conclusion:
  > Neighbourhood groups Queens and Manhattan have maximum number of reviews {assuming the reviews to be positive}. Hence most busiest hosts belong to these.
  
  > 10 Most listed neighbourhoods that belong to Brooklyn and Manhattan are all highly reviewed as well.
  
  > Dona from Jamaica, Queens is the busiest host according to above analysis.
  
● Analysed and explained the reason for traffic in different areas using relation between number of reviews, neighbourhood group, room type, price and availability among different neighbourhood groups. And obtained the following conclusion:

  > Most neighbourhoods with high listings are present in Manhattan making it a busy place.
  
  > The private rooms are mostly of average price, which makes them affordable to wide range of people and are highly reviewed too to make them prone to traffic.
  
  > The neighbourhoods with most listings like- Bedford-Stuyvesant, Williamsburg in Brooklyn and Harlem in Manhattan, have most number of private rooms explaining the      traffic there.
  
  > Though the shared rooms have least average price, due to lesser listings of this type and it’s least preference, the traffic cannot be expected.
  
  > Brooklyn and Manhattan having least availability(most-booked) are expected to be prone to traffic.
  
  > Thus, number of listings, number of reviews, affordability etc contribute for traffic in certain areas.
  
● Calculated the average revenue per host and plotted it for different neighbourhood groups. Manhattan is found to have highest average revenue.

● Depicted the price distribution among neighbourhood groups using Violin plot and observed that:

  > Brooklyn has an avg price of $80.
  
  > Manhattan has highest range of price with average around $150.
  
  > Queens and Staten Ialand have nearly same median price.
  
  > Bronx, Staten Island and Queens have prices concentrated towards the median price.
  
  > Staten Island has almost normal distribution of price.
  
Conclusion:

The analysis would have been more specific/systematic if the reviews were broken down into positive and negative one or scaled according to emotion specified in it (like(0-5)). However throughout this analysis we have assumed reviews to be positive only. And the analysis would definitely help in making better business decisions.



