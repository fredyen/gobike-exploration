# Exploration GoBike 2017
## by Frederick Yen


## Dataset

The dataset being used for exploration is the 2017 Ford GoBike trip data dataset. It contains 13 columns with 519,700 non-null entries. Each entry contains trip info such as duration (int), start/end time (object), bike/station ID (int), station lat/long (float), and more.

## Summary of Findings

1. The busiest hours are pretty much consistent throughout the month with rush hours occurring around 8AM and 5PM. This will be included in explanatory analysis.
2. Overall similar distribution of durations through out the months.
3. Subscribers use the bikes the most around rush hour while the customers have no outstanding peaks of usage throughout the day. This will be included in explanatory analysis.
4. Subscribers on average has shorter rides (8 mins) comparing to the customers (11 mins). This will be included in explanatory analysis.
5. Overall trend of number of rides through the months are similar when comparing subscribers to customers. Even though the number of rides for subscribers are 4~5 times more than the customers, most rides happened between September and November for both of the user groups.
6. Customers on average have longer trips each month comparing to the subscribers. The trips are especially longer for the summer break months (June, July, and August). This will be included in explanatory analysis.
7. Customers tend to have the longest rides when the bikes are checked out around noon. On the other hand, subscribers have a relative consistent ride duration through the whole day.
8. The user behavior differences for ride start hours and durations was very interesting. With the above insight and plots, you can see huge fluctuations of ride durations for the customers but this is not the case for the subscribers.


## Key Insights for Presentation

The main thread of the presentation will be exploring the user behavior differences between the subscribers and customers. The visualizations will include the multi-variable plots that are related to user types as well as the location graph for the stations.

## Resources

1. https://stackoverflow.com/questions/46623583/seaborn-countplot-order-categories-by-count
2. https://stackoverflow.com/questions/52010388/value-counts-on-multiple-columns-with-groupby
3. https://stackoverflow.com/questions/20461165/how-to-convert-index-of-a-pandas-dataframe-into-a-column
4. https://www.bigendiandata.com/2017-06-27-Mapping_in_Jupyter/
5. https://re-thought.com/pandas-value_counts/
6. https://stackoverflow.com/questions/36684013/extract-column-value-based-on-another-column-pandas-dataframe
7. https://www.kaggle.com/residentmario/faceting-with-seaborn
8. https://seaborn.pydata.org/generated/seaborn.distplot.html
9. https://seaborn.pydata.org/generated/seaborn.pointplot.html#seaborn.pointplot
10. https://stackoverflow.com/questions/38082602/plotting-multiple-different-plots-in-one-figure-using-seaborn
