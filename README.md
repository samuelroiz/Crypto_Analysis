# Crypto_Analysis


## Project 

This project was created to try to understand the performance of the crypto currency, it's popularity and compare it to the performance of the dollar.

Our Objective was to answer four main questions.
1. Is crypto a good investment?
2. How does crypto compare to the dollar?
3. Did the pandemic have any effect over crypto currencues?
4. Is there a relationship between the performance of crypto currencies and the dollar?

To be able to answer this questions we took our data from two api's :
1. Nomics API
2. ExchangeRates API


The branches for this project are called: 
<b> Sven </b>: Here we did an analysis of the dollar in comparison to crypto currencies and a comparison of the dollar vs the bitcoin during the last year.

<b> Value </b>: this branch was used to retrieve and do an analysis of each separate crypto currency to be able to later plot them, here we also did some simple bar plots to understand the performance and crypto environment.

<b> Comparison </b>: This branch, is extremely related to the Value branch, we took that code as starter and created a user interface for the user to be able to input several currencies he is interested in and have a simple analysis and comparison of those desired currencies.

<b> Plots </b>: On this branch we did some more complex plots, like bubbles and a line chart for the market capfor the whole year to understand the performance of the crypto currency during the pandemic and post pandemic.

After realizing our investigation and supported in our findings we arrived at several diferent conclusions.
1. Right now and for the last year Crypto was a good and safe investment, of our 100 samples only 2 had a negative revenue result on the last 365 days. 
  Although it was a safe investment, the crypto market is mostly represented by the Bitcoin being by far the most popular, pricier and known crypto currency.
2. Crypto and the dollar have a small relationship on their performance, but there is a stronger relationship between the dollar and Bitcoin, this is the most popular and known Crypto currency. 
3. The pandemic had a big impact over Crypto currencies but it also had a bigimpact over the dollar investment.

## What the data tell us

### <b> <i> How many cryptocurrencies are there? What are they worth? </i> </b> 
<p>
More than 13,000 different cryptocurrencies are traded publicly, according to Nomics.com, a market research website. And cryptocurrencies continue to proliferate, raising money through initial coin offerings, or ICOs. The total value of all cryptocurrencies on Oct. 22, 2021, was more than $2.5 trillion, having fallen off an all-time high above $2.6 trillion days earlier. The total value of all bitcoins, the most popular digital currency, was pegged at about $1.2 trillion.
</p>

<b> <i> Did the pandemic affect the crypto market? Positively? Negatively? No effects? </i> </b>

![Crypto Market Over the Pandemic](https://github.com/samuelroiz/Crypto_Analysis/blob/main/Images_sven/crypto_over_the_years.png)

<p> As we can see, the bar chart shows how much the data has evolved over the pandemic. The pandemic started in 2021 and has been in the pandemic ever since. The crypto market shows its growth at the beginning of the pandemic and has grown ever since with some drops along the way. The bar chart still shows some significant increases in the crypto market and will keep growing even if the pandemic is finished. </p> 

![Pandemic Market Bar Chart](https://github.com/samuelroiz/Crypto_Analysis/blob/main/Images_sven/Pandemic_Market_Bar_Chart.png)

<p> Another bar chart showing how the pandemic increased the crypto market cap. The following bar chart displays the crypto currency market during the years of the pandemic. As you can see, the market cap was around five hundred thousand. Once the pandemic hit, the crypto currency sky rocketed to a maximum of 2.5 le 12.  </p>


<b> <i> Does the USD and Bitcoin value have any correlation with each other? </i> </b> 

![Dollar Change vs Bitcoin Price](https://github.com/samuelroiz/Crypto_Analysis/blob/main/Images_sven/USD_vs_Bitcoin_2010to2021_with_r_squared.png)

<p> The following graph shows the correlation between dollar change and bitcoin price. It used the linear regression model and shows an r-squared of .83. The r-squared tells us how much do they have a correlation with each other. The closer the r-squared is to a whole number, the connection between two variables relies on each other. Since it had an r-squared of .83, then the dollar price indicates the bitcoin price. If the value goes down, then either will go down. Therefore, dollar price and bitcoin price both share a relationship. </p> 

<b> <i> Does the USD and Cyrpto Market Capacity have any correlation with each other? </i> </b> 

![USD vs Crypto Market Graph](https://github.com/samuelroiz/Crypto_Analysis/blob/main/Images_sven/USD_vs_CyrptoMarket_Pandemic_with_r_squared.png)

Unlike the graph before, the dollar price and crypto market cap have an r-squared of .47. The r-squared is considered to be a weak correlation between the two indicators. With this information, we will not look too much into the dollar price and crypto market cap together since they do not share a relationship. 


