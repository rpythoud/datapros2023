---
layout: default
---

<div style="text-align: center;">
    <img src="./img/Blockbuster.png" alt="Logo" style="width: 60%; margin: auto; display: block;">
</div>

## Meeting invitation

Welcome to Blockbuster Inc., the only movie producer obsessed on achieving the highest financial results in the film industry. You have the chance to take part of our latest board meeting, where our hard working interns sum up their most promising findings. During this meeting of the highest importance, they will expose the secret sauce that turns a movie into a worldwide success. In case you would be reluctant to attend this summit, be assured that the investigation presented will be mind-blowing, since our newly hired interns were given unlimited access to our next generation quantum compute clusters and were generously compensated for their job. We strongly encourage you to attend the meeting.


### 8:00-8:30: Introduction to the dataset | Speaker: Romain

For this investigation, the CMU Movie Corpus dataset will be used to take a dive into the realms of movie industry. This dataset includes movie titles, featured actors, related genre, corresponding box office revenues and more. Regrettably, the dataset does not include any information on movies ratings, a useful component of our analysis as it includes the overall public perception. To adress this issue, we supplemented it the main dataset with the IMDb Movie Dataset, which provides the movie ratings. 

Furthermore, a quick look at the main dataset shows that most of the box office revenues data related to the films are missing. This observation is confirmed by the following plot.

<div style="text-align: center;">
    <img src="./img/Romain_missing_data.png" alt="plot1" style="width: 70%; margin: auto; display: block;">
</div>

Although the proportion of missing revenues data is high, an analysis on the overall box office revenues could still provide relevant insights as the total number of remaining is still significant.

A plot of the movie revenues over the years is done below.

<div style="text-align: center;">
    <img src="./img/Romain_regression.png" alt="plot2" style="width: 80%; margin: auto; display: block;">
</div>

From this plot, we can see that the increase of movie revenues over the years follow an exponential distribution. This is further confirmed by the positive slope of the linear regression on the log axis of the data points. This exponential increase in box office revenues over the years is due to the compounding effect of monetary inflation year over year. We can take into account this effect by adjusting the revenues in usd using inflation data provided by the US Consumer price index (CPI). Although other effects can affect the revenue distribution over the years like the size of the adressable market, the resulting plot is a more reliable representation of the financial success of a movie through history.

<div style="text-align: center;">
    <img src="./img/Romain_adjusted_inflation.png" alt="plot3" style="width: 70%; margin: auto; display: block;">
</div>


### 8:30-9:00: Genres decomposition | Speaker: Adam

### 9:00-9:30: Coffee break

<div style="text-align: center;">
    <img src="./img/coffee_break.jpg" alt="plot4" style="width: 70%; margin: auto; display: block;">
</div>

### 9:30-10:00: Gender and revenues relationship | Speaker: Gilles

{% include gilles_slider_plotly.html %}

### 10:00-10:30 Actors influence on the Box office | Speaker: Marko

### 10:30-11:00 Topic analysis, summaries processing | Speaker: Dusan

### 11:00-12:00 Lunch together !!!





