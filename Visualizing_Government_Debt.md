## Visualizing Government Debt

### Part I

The OCED website has a handy tool for visualizing the data requested. While this bar chart is helpful for assessing very general trends there are some aspects it's lacking such as a well defined y-axis or any sense of time. The colors indicating different countries is helpful, but there may a better way to seaparte individual countries and view their data. 

<iframe src="https://data.oecd.org/chart/6Aji" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6Aji" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2020</a></iframe>

### Part II


Its always a challenge to visualize a complex dataset, this is made especially complicated when considering time series information. The data provided by the Organization for Economic Co-operation and Development (OECD) is a prime example of time series data trying to convey a complex idea across many different data points (in this case countries). Utilizing a grid of charts is helpful for this. At times information density can be too high if a designer attempts to visualize multiple data points across time. Breaking the different data points into a facet grid can allow for each individual point to stand on its own. Since the OCED Debt to GDP ratio data is spread across a 23 year time span looking at each country individually and giving each country it's own corresponding line chart can add legibility to an unwieldy dataset. This function in Flourish was simple to use and made the data easily digestable for me. 

<div class="flourish-embed flourish-chart" data-src="visualisation/5574665"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Part III

While seeing each countries Debt to GDP ratio in a grid is helpful, it doesnt fit the needs of all kinds of users. Take an economist for example. Knowing the trend of debt to GDP for a country may not offer enough information. If an economist wanted to see Japan's debt to GDP ratio in 1998 to understand Japan's deflation crisis and how that affected other economies during the same time period the chart above would require a significant amount of parsing to gather that information. This dilemma in mind I wanted to design an alternative view that could accomplish this task. To do so I switched the filtering criteria from the country to the year, this way a viewer could look at specific time periods. I also added a data selector; the addition of this data selection filter allows a viewer to look at the overall trend or choose a specific year. A viewer could now select 1998 and view Japan's debt to GDP ratio and compare it to other countries during that time period. This filter allows for a sort of zoom in view of the overall grid chart on data a person is interested in. I chose an area chart so comparisons could easily be made, simply by looking at the height of the shaded area you can see what countires had the highest debt to GDP ratio and establish trends on the grid view. I also added a descriptive title so users can contextualize the large volume of information they're seeing. 

<div class="flourish-embed flourish-chart" data-src="visualisation/5593399"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
