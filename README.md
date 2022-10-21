# Diamonds Data Exploration

## Dataset

The data consists of information regarding 54,000 round-cut diamonds, including
price, carat, and other diamond qualities. The dataset can be found in the
repository for R's ggplot2 library [here](https://github.com/tidyverse/ggplot2/blob/master/data-raw/diamonds.csv),
with feature documentation available [here](http://ggplot2.tidyverse.org/reference/diamonds.html).


## Summary of Findings

In the exploration, I found that there was a strong relationship between the
price of a diamond and its carat weight, with modifying effects from the cut,
color, and clarity grades given to the diamond. The relationship is
approximately linear between price and carat when price is transformed to be on
a logarithmic scale and carat transformed to be on a cube-root scale. I found a
somewhat surprising result initially when the marginal trend for the cut, color,
and clarity variables indicated that higher diamond quality was associated with
lower price. However, higher diamond quality was also associated with smaller
diamonds. When I isolated diamonds of a single carat weight, there was a clear
positive relationship between higher diamond quality and higher diamond price.

Outside of the main variables of interest, I verified the relationship between
diamond carat weight and its x, y, and z dimensions. For the dataset given,
there was an interesting interaction in the categorical diamond quality
features. The lower clarity grades looked like they had slightly better
distribution of cut and color grades than diamonds with the higher clarity
grades.


## Key Insights for Presentation

For the presentation, I focus on just the influence of member age groups, member gender, user type, duration in hour, start and end stations
and leave out most of the intermediate derivations. I start by introducing the distribution of start and end time of the day also the start and end day of the week.

Afterwards, I introduce each of the independent variables one by one. To start, I use the bar plots of start and end time of the day across member age groups. The other 4 independent variables, member gender, user type, duration in hour, start and end stations are covered afterwards using cluster bar chat.