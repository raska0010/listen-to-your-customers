**Capstone Project from Kamruddin A., Theresa B.,  Sining D. & Robert S. ; Data Analytics Bootcamp by neuefische, 2023**

![](https://media.giphy.com/media/vgzyAN43REBCoI4ns0/giphy.gif)

## Listen to your  customers

### Analysing online reviews to refine business' service quality


**Introduction**

In this repository we will analyse YELP online reviews to refine restaurant quality. 
<br>
This is devided in two steps: Taking a closer look to the business attributes, if there is a correlation between the attributes and star ranking.
In the second step the sentiment analysis is in the center of attention. To get to know if we can implement the customer reviews to improve the star ranking of restaurants.

**First of all: Let's clean the data!**
<br>
First we downloaded the Dataset provided by Yelp.com

Then we took a look at the business dataframe and cleaned it.
Since 39% of customers trust a business with at least 3.5 stars and 79% of customers trust a business with at least 4 stars, we decided to take a closer look to the 3.5 star ranked restaurants in Pennsylvania. Why Penssylvania? Since there are the most reviewed restaurants in the US we will have a lot of data and reviews to analyse.
<br>
**For further data cleaning check the 'data_cleaning' notebook!**
<br>
### Yelp Business Attributes

First we checked if there is a correlation between business attributes and star ranking.
This you can see in the 'EDA_yelp.ipynb' file.

### Yelp Customer Reviews

In the last step we used sentiment analysis to check the customer reviews for potential for improvement. 3.5 rankings could be positive or negative, that is why we first filtered to the negativ ones. This happens in the 'SentimentAnalysis' notebook.

The review analysis occurs in the 'reviews_analysis' notebook 
We use spaCy to find out what customers are complaining about.
There are 4 categories we analysed: food, service, ambience & location and price. To visualize the matches we used wordclouds. 
The most matches were found in food & service. 


**For our final presentation you can  [click](https://www.canva.com/design/DAF0avXAMVE/k72AP0zTyQgdv65lY87ZMg/view) here**

