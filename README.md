# California Housing Price

## by Timothy Adebisi


## Dataset

The dataset contains 20,640 observations and 10 features. The features are listed below:
1. longitude
2. latitude
3. housing_median_age (Years)
4. total_rooms
5. total_bedrooms
6. population
7. households
8. median_income (USD)
9. median_house_value (USD)
10. ocean_proximity

The dataset can be found [here](https://www.kaggle.com/datasets/camnugent/california-housing-prices?select=housing.csv) on the page including the data features.

## Summary of Findings

In the exploration, I found out that there is a strong positive correlation between Income and House Value, the average income of an household correlates with the value of the house they occupy. I also found out that houses that are on the inland cost less that those in the water areas. Houses close to the ocean and the Bay area are relatively high irrespective of their age.

There were 207 empty observations was dropped in the dataset. Using the categorical feature `ocean_proximity`, most of the houses in the dataset are less than an hour to the ocean. During exploration, there is a linear relationship between thr `median_income` and `median_house_value`. I also found out that `housing_median_age` does not have any relationship with `median house_value`. Another suprisng thing is that the closer the houses are to the `ocean` or `bay_area`, the higher the `median_house_value` as it is on the map.

## Key Insights for Presentation

For the presentation I focused on the relationship between `median_income` and `median_house_value` using a scatter plot to show their correlation. I then showed the distribution of `median_income`, `housing_median_age` and `median_house_value`.
Afterwards, I plot a chart show the spacial distribution of the houses, their location and value.