---
layout: default
---

<div style="text-align: center;">
    <img src="./img/Blockbuster.png" alt="Logo" style="width: 60%; margin: auto; display: block;">
</div>

## Meeting invitation

Welcome to Blockbuster Inc., the only movie producer obsessed on achieving the highest financial results in the film industry. You have the chance to take part of our latest board meeting, where our hard working interns sum up their most promising findings. During this meeting of the highest importance, they will expose the secret sauce that turns a movie into a worldwide success. In case you would be reluctant to attend this summit, be assured that the investigation presented will be mind-blowing, since our newly hired interns were given unlimited access to our next generation quantum compute clusters and were generously compensated for their job. We strongly encourage you to attend the meeting.


### 8:00-8:30: Introduction to the dataset | Speaker: Romain

For this investigation, the CMU Movie Corpus dataset will be used to take a dive into the realms of movie industry. This dataset includes movie names, actors, release date and box office revenues. The dataset does not include any information on movies ratings, a useful component of our analysis as it includes the overall public perception. To adress this issue, we supplemented it with the IMDb Movie Dataset providing the movie ratings. Furthermore, a quick look at the main dataset shows that most of the box office revenues data related to the films are missing. This observation is confirmed by the following plot.

<div style="text-align: center;">
    <img src="./img/Romain_missing_data.png" alt="Logo" style="width: 80%; margin: auto; display: block;">
</div>

Although the proportion of missing revenues data is high, an analysis on the overall box office revenues could still provide relevant insights as the total number of remaining is still significant.

A plot of the movie revenues over the years is done below.

<div style="text-align: center;">
    <img src="./img/Romain_regression.png" alt="Logo" style="width: 80%; margin: auto; display: block;">
</div>

<div style="text-align: center;">
    <img src="./img/Romain_adjusted_inflation.png" alt="Logo" style="width: 80%; margin: auto; display: block;">
</div>

### 8:30-9:00: 
{% include gilles_slider_plotly.html %}




