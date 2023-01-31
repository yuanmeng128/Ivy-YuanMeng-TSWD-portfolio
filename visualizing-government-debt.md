| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Assignment: Visualizing government debt

## Part 1: Working with web-based visualization tools and data

### General Government Debt Bar Chart (Year 2021)

The bar chart is developed by the built-in tool from the OECD website and renders on my github portfolio. The bar chart shows the debt-to-GDP ratio of several countries in 2021. 

<iframe src="https://data.oecd.org/chart/6Y2T" width="900" height="675" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6Y2T" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2021</a></iframe>

## Part 2: Working with Flourish

### General Government Debt Sparklines

This visualization display the debt-to-GDP ratios from 1995 to 2021 of different countries using grid line charts. 

<div class="flourish-embed flourish-chart" data-src="visualisation/12596848"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### General Government Debt World Map (Year 2021)

The heat map displays the debt-to-GDP ratio of each country in 2021. With the heat map, the location of each country is shown clearly and their sizes of the debt-to-GDP ratio are displayed by the shade of the "orange color". The larger the ratio, the darker the color. The map is also interactive and you can check the detailed ratio value of each country by moving your cursor on the country.

<div class="flourish-embed flourish-map" data-src="visualisation/12597280"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Discussion about these different methods of visualization

The bar chart is usually used to show comparisons among discrete categories. One axis of the chart shows the categories to be compared. The other axis shows the measured value. If no specific orders of bars are required, bars on the chart are usually arranged from highest to lowest or lowest to highest to make the comparision more clear. In our "General Government Debt Bar Chart", we compare the debt-to-GDP ratios of countries in 2021. By arranging the bars from the lowest to the highest, readers can easily identify Japan has the highest debt-to-GDP ratio, Estonia has the lowest ratio and the ranking of other countries. However, the bar chart has an obvious shortage that it can only compare the ratios of different countries in a single year. It's true that we can group the data based on the year and include several groups in the bar chart to compare countries' ratios in different years. However, the resulted bar chart would be too long and its clarity would be greatly reduced.

The sparkline is a very small line chart, typically drawn without axes or coordinates. It presents the general shape of the variation (typically over time) in some measurement in a simple and highly condensed way. Since the size of the sparkline is very small, several sparklines can be grouped together. In our "General Government Debt Sparklines", each sparkline shows the changing pattern of a specific country's debt-to-GDP ratio and sparklines of different countries are grouped together. Since the size of each sparkline is small, it's adoptable to draw each country's sparkline and group them together. So, our sparklines can display the changing trends of each country's debt-to-GDP ratio. However, the disadvantages are apparent. Firstly, since the sparkline just shows the general trend, readers cannot get detailed data or information from the sparkline. Secondly, since the line of each country is put in different sparkline charts, it's difficult to compare the trend of different countries. 

The world map can build the data on the map. In our "General Government Debt Map", the size of each country's debt-to-GDP ratio is shown by the shade of the color of the country's map plate. So, when looking at the map, the audience can intuitively know which country has the higher ratio and which country has the lower ratio. Below are the reasons why I choose the map to visualize the general government debt. First, the map can immediatly tell the audience the distribution of countries with the highest or lowest ratio in the world. Secondly, since the map is an interactive visualization, audience can get the exact ratio value by moving their cursors on the country location. The most significant disadvantage of map is that somtimes it's difficult to compare the color shade. So, it is difficult to  get the exact ranking of countries by looking at the map.

In summary, the bar chart is good at comparing discrete categories on a measure, but the amount of categories which can be indluded without influencing the chart clarity is limited. The sparkline is used to show the general trend of a measurement. Since the size of a sparkline is small, many sparklines can be grouped together. However, unlike the bar chart and the interactive map, audience cannot get detailed data from sparklines. The map can show the distribution of countries intuitively. But it's difficult to use map to show the chaning pattern over time like sparklines. It's also difficult to show the exact ranking of countries like bar chart. So, we should select visuliazation tools based on the characteristics of each visualization type and our goals.

## Reference:

Wikipedia contributors. (2023a, January 14). Bar chart. Wikipedia. https://en.wikipedia.org/wiki/Bar_chart 

Wikipedia contributors. (2022, October 7). Sparkline. Wikipedia. https://en.wikipedia.org/wiki/Sparkline
