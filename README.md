# Crypto Analysis

## Project

This project was created to understand the performance of cryptocurrencies, their popularity, and how they compare to the performance of the dollar.

Our objective was to answer four main questions:
1. Is crypto a good investment?
2. How does crypto compare to the dollar?
3. Did the pandemic have any effect on cryptocurrencies?
4. Is there a relationship between the performance of cryptocurrencies and the dollar?

To answer these questions, we gathered data from two APIs:
1. Nomics API
2. ExchangeRates API

## Branches

The branches for this project are:

**Sven**: Analysis of the dollar in comparison to cryptocurrencies and a comparison of the dollar vs. Bitcoin over the last year.

**Value**: Analysis of individual cryptocurrencies to plot their performance. Simple bar plots were created to understand the crypto environment.

**Comparison**: User interface for inputting multiple currencies to compare and analyze their performance.

**Plots**: More complex plots, like bubble charts and line charts, for market cap over the year to understand the performance of cryptocurrencies during and after the pandemic.

## Findings

1. **Crypto as an Investment**: Over the last year, crypto has been a good and relatively safe investment. Out of 100 samples, only 2 had a negative revenue result. However, the crypto market is predominantly represented by Bitcoin, the most popular and valuable cryptocurrency.
2. **Crypto vs. Dollar**: There is a small relationship between the performance of crypto and the dollar, but a stronger relationship exists between the dollar and Bitcoin.
3. **Pandemic Impact**: The pandemic significantly impacted cryptocurrencies and the dollar investment.

## What the Data Tell Us

### How many cryptocurrencies are there? What are they worth?

More than 13,000 different cryptocurrencies are traded publicly, according to Nomics.com. The total value of all cryptocurrencies on Oct. 22, 2021, was over $2.5 trillion. The total value of all bitcoins was pegged at about $1.2 trillion.

### Did the pandemic affect the crypto market? Positively? Negatively? No effects?

![Crypto Market Over the Pandemic](https://github.com/samuelroiz/Crypto_Analysis/blob/main/Images_sven/crypto_over_the_years.png)

As shown in the bar chart, the crypto market grew significantly during the pandemic and has continued to grow, with some fluctuations along the way.

![Pandemic Market Bar Chart](https://github.com/samuelroiz/Crypto_Analysis/blob/main/Images_sven/Pandemic_Market_Bar_Chart.png)

Another bar chart showing how the pandemic increased the crypto market cap. The market cap was around five hundred thousand before the pandemic and skyrocketed to a maximum of 2.5 trillion during the pandemic.

### Does the USD and Bitcoin value have any correlation with each other?

![Dollar Change vs Bitcoin Price](https://github.com/samuelroiz/Crypto_Analysis/blob/main/Images_sven/USD_vs_Bitcoin_2010to2021_with_r_squared.png)

The graph shows a correlation between dollar change and bitcoin price with an R-squared of 0.83. This indicates a strong relationship between the dollar price and bitcoin price.

![USD and Bitcoin Price Change](https://github.com/samuelroiz/Crypto_Analysis/blob/main/Images_sven/dollar_change_vs_bitcoin_change.png)

The price change between dollars and bitcoin shows a high correlation. Dollar changes can predict bitcoin price movements.

### Does the USD and Crypto Market Capacity have any correlation with each other?

![USD vs Crypto Market Graph](https://github.com/samuelroiz/Crypto_Analysis/blob/main/Images_sven/USD_vs_CyrptoMarket_Pandemic_with_r_squared.png)

The graph shows an R-squared of 0.47 between dollar price and crypto market cap, indicating a weak correlation.

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/samuelroiz/1af49ec9eea365bc845ba04c5071a976) for details on our code of conduct and the process for submitting pull requests.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For available versions, see the [tags on this repository](https://github.com/your/project/tags).

## Authors

* **Samuel Roiz** - *Data cleaning, API keys, Plotting, Data analysis* - [GitHub](https://github.com/samuelroiz)
* **LaQuita Williams** - *Plotting* - [GitHub](https://github.com/laquita44)
* **Leo Lima** - *Data cleaning, API keys* - [GitHub](https://github.com/Leolima539)
* **Kevin Perez** - *Plotting* - [GitHub](https://github.com/KevinKVNPR)

See the list of [contributors](https://github.com/samuelroiz) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://gist.github.com/samuelroiz/1af49ec9eea365bc845ba04c5071a976) file for details.

## Acknowledgments

* [Poly](https://www.poly.network/#/)
* [Nomics](https://nomics.com/)
* [Exchange Rates](https://exchangeratesapi.io/)
* USC Data Visualization
* CSUN Mathematics
