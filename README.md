This is a simple project that explores global population trends. 
The goal is to investigate how population trends vary across countries and continents.

The objectives were to examine: 
1. The weighted population growth rate by continent:
A weighted average growth rate was calculated for each continent by first calculating assigning a weight to each country per continent.
This weight was multiplied by the corresponding growth rate and summed to produce the continent's weighted population growth rate.
This provides a more realistic measure compared to a simple average to account for larger countries that contribute more to the overall growth.

2. The relationship between growth rate and population size:
A scatter plot was created to explore the relationship between population size (using a log scale)and growth rate.
Each point on the plot represents a country, and the different colors distinguish between the continents.
A logarithmic scale was applied to the population axis to improve visibility as many countries have overlapping population sizes.

3. How much each continent contributes to the world population.
The proportion of the world’s population residing in each continent was analyzed.
This highlights the global distribution of population and shows how heavily population is concentrated in certain regions.

The appropriate visualisation techniques were applied to each of the investogations above to improve interpretability.

The dataset was sourced from Kaggle via https://www.kaggle.com/datasets/iamsouravbanerjee/world-population-dataset. 
More information on it is available by following the link. The "2022 Population" attribute is what was used.

Tools and libraries used include: 
1. Python
2. pandas
3. NumPy
4. Matplotlib

The key insights obtained from this exercise were that:
1. Most countries cluster around a ~1% population growth rate.
2. Countries in Africa exhibit relatively higher growth rates compared to other continents.
3. European countries generally exhibit lower growth rates except for a few outliers, indicating slower population increase.
4. Population is highly concentrated in Asia, followed by Africa, meaning a few continents dominate the global population share.


