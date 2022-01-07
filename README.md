Check out the [jupyter notebook](https://github.com/jcummingsutk/london_housing/blob/master/london_housing.ipynb)

# Summary

In this project I aim to find which boroughs of London have increased their value most over the past 10 years.

To accomplish this goal, I first import the open data from the London database on average housing prices per month per borough. After taking a quick look at the data, I tidy the data from a wide state to a tall state, remove missing values, and remove unnecessary data of housing prices for regions other than London boroughs.

After cleaning and transforming the data to a reasonable state, I group and aggregate the data by year and borough, as the data is given in terms of monthly averages and not yearly.

We plot a few of the boroughs trends over time, seeing that the three that we plot have the same behavior. More could be done examining this temporal dependence on the data, and perhaps that is a project for a later date.

Finally, we define a function to capture the largest N increases in housing price ratios and visualize them through a bar chart We find that Waltham Forest has the highest ratio of 2021 housing prices to 2001 housing prices with a ratio of 4.1, followed closely by Hackney.

As far as continuing this analysis, the most obvious extension would be a finer analysis of the temporal dependence of the housing market in London, as we have used yearly data, but the monthly data is available.

As far as challenges, it is always challenging to clean and transform data into a usable format. It seems that there will always be extensive stack exchange searches. The important thing for me is knowing the vocabulary, which comes with time and listening to lectures and reading projects.
