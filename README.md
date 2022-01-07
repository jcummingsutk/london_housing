Check out the [jupyter notebook](https://github.com/jcummingsutk/london_housing/blob/master/london_housing.ipynb)

# Summary

In this project I aim to find which boroughs of London have increased their value most over the past 10 years.

To accomplish this goal, I first import the open data from the London database on average housing prices per month per borough. After taking a quick look at the data, I tidy the data from a wide state to a tall state, remove missing values, and remove unnecessary data of housing prices for regions other than London boroughs.

After cleaning and transforming the data to a reasonable state, I group and aggregate the data by year and borough, as the data is given in terms of monthly averages and not yearly.

I plot a few of the boroughs trends over time, seeing that the three that we plot have the same temporal behavior. More could be done examining this temporal dependence on the data, and perhaps that is a project for a later date.

Finally, I define a function to capture the 10 boroughs with the largest increases in housing price ratios and visualize them through a bar chart. I find that Waltham Forest has the highest ratio of 2021 housing prices to 2001 housing prices with a ratio of 4.1, followed closely by Hackney.

As far as continuing this analysis, the most obvious extension would be a finer analysis of the temporal dependence of the housing market in London, as we have used yearly data, but the monthly data is available. Even simpler, one could look at all the boroughs behavior, rather than simply the top N.

As far as challenges, it is always challenging to clean and transform data into a usable format. It seems that there will always be extensive stack exchange searches. The important thing for me is knowing the vocabulary, which comes with time and listening to lectures and reading projects. It also helps to have this project for future reference, so I can see what I did and copy it in another project.
