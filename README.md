# (Data analysis with WeRateDogs Twitter Archive Data)
## by (Joshua Enam Semanyoh)


## WeRateDogs Twitter Data Analysis and Visualization

Data analysis has always been a fascinating skill area which allows all data to be gathered from all sources, assessed and cleaned and then explored to produce fascinating analysis and visualizations.

Data that was gathered with a lot of quality and tidiness issues can be transformed into beautiful dashboards, visualizations and meaningful reports for various reports.

The WeRateDogs trio of datasets wrangled in this ALX Udacity Data Analyst Nanodegree Program project is no exception.

Find below my insights and visualizations! They are quite simple but already give invaluable insights that can be explored further. Come along!



## Dataset Description

There are three datasets used for this project.

### Dataset 1 - WeRateDogs Twitter Archive Dataset
The WeRateDogs Twitter archive dataset used contains basic tweet data for almost 2400 tweets. The WeRateDogs twitter page is a page that shares beautiful pictures of different breeds of dogs and rates them using a unique measure where the numerator is always higher than 10 (the denominator). For example, 13/10.

### Dataset 2 - Twitter API WeRateDogs Dataset
We pull retweet count and favorite count data from thid dataset. This will be combined with the Twitter Archive Dataset for a better analysis.

### Dataset 3 - Image Predictions Dataset
A machine learning model was used to create this prediction dataset. The algorithm is able to predict whether a picture in a specific tweet contains a particular dog breed with varying degrees of accuracy.



## Research Questions

1. What were the most popular breeds predicted by the image prediction model?

2. What was the most popular dog stage in the twitter_archive dataframe?

3. Were the ratings affected by the retweet counts and favorite counts?

4. Which year has the most tweets?

5. How has retweet count changed over the years?


## References

1. https://pandas.pydata.org/docs/user_guide/index.html#user-guide
2. https://stackoverflow.com/questions/22649693/drop-rows-with-all-zeros-in-pandasdata-frame
3. https://classroom.udacity.com
4. https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.melt.html
5. https://cran.r-project.org/web/packages/tidyr/vignettes/tidy-data.html
6. https://datagy.io/pandas-extract-date-from-datetime/#:~:text=The%20Quick%20Answer%3A%20Use%20df%20%5B%E2%80%98date_column%E2%80%99%5D.dt.date%20To%20Extract,Contents%20What%20is%20the%20Pandas%20Datetime%20dt%20Accessor
7. https://datagy.io/pandas-scatter-plot/#:~:text=Pandas%20makes%20it%20easy%20to%20add%20titles%20and,accepts%20a%20string%20and%20sets%20the%20x-label%20title