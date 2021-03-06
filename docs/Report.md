# teamFSV - Assignment 1 

# Introduction: 
The theoretical assumption for this research is the "Median Voter’s theorem" that states that under majority rule voting systems, political parties should position themselves close to
the outcome preferred by the median voter.

In order to test this theory we thought of observing the 12 different election results for Switzerland. Our main goal is to understand if there is a relatioship between the percentages of votes per election and the political position of the parties. Our research was made on the dataset provided by ParlGov, a data infrastructure for political science and contains information for all EU and most OECD democracies. 

# Our variables:
To understand and observe Switzerland's elections we needed to clean and recode some variables. 

- The first step was to select only the years we were interested in (from 1975 to 2019) and the country. 

- Secondly, we created the variable `pol_pos`that describes the political position of each party, divided in three categories: left - center - right. This new variable is based on the pre-existing `left_right` that ranges from 0 to 10; we divided it by 3, obtaining the 3 final categories. 

- Lastly, we kept only significant variables like: name of the country and share of vote for each election. 

# Plots

To perform our analysis we made some informative plots, describing the results of the selected national elections: 


## Plot one

![plot1](https://github.com/DataAccess2020/teamFSV/blob/master/plot/plot1.png)

In the first plot, we observe the years *2007, 2011, 2015, and 2019*.
What we notice here is that the right wing has the majority of votes in all the four years, collecting more than 25% of the votes in all the cases. The left and the center follow, and their shares of votes are more close to each other, obtaining about 20% of votes for the left and about 15% for the center, in all the years considered. We can also point to the fact that the results for right and left see a minimum in 2019 in respect to the years considered. 

From those 4 election we can clearly observe that the central party did not win, therefore this first plot provide evidence agains the "Median Voter’s theorem".

## Plot two 

![plot2](/plot/plot2.png)

In the second plot, we observe the years *1991, 1995, 1999 and 2003*. 
The first thing that comes to our attention is how the situation changes from 1991 to 2003: the center was the political position that gained more votes in 1991, and it became the last of the three in 2003. What happen is that the center had about 20% of votes in 1991, then its results decreased a little in 1995 and 1999, and then they were about 15% in 2003. 

On the other hand, the left went from having less than 20% of votes in 1991, to having about 24% in 2003. The most accelerating was the right, which started with a little more than 10% in 1991, reached 15% in 1995, got about 23% of votes in 1999 and over 25% in 2003. So in 2003 the right reached the result that it then kept for the four subsequent elections. 

## Plot three 


![plot3](/plot/plot3.png)


In this plot we consider the years *1975, 1979, 1983 and 1987*. 


Once again a different situation, we observe here that in 1975 the left had the highest percentage of votes. It reached 25% in that year, then it declined in the following elections, reaching about 20% in 1987. Here we see that the left and the center had a similar percentage of votes in the first three years, while the right remained isolated all the time, with a percentage of votes of about 10% in all the years considered (even though it was slowly increasing). We can also notice that the votes for the left slowly decreased during the years, while the votes for the center increased from 1975 to 1979, and then decreased in the following elections. 

# Conclusion:

In conclusion, among the 12 different elections that were here analysed, the central parties had the majority of votes only in 3 occasions (1983 - 1987 - 1991). 

Also, the center parties were the ones with the smallest share of votes in the last *six elections*. It is also interesting to notice that through all the years considered, the results for the left and the center are always more similar to each other than they are to the results of the right. Could it be that the left and the center have more similar features, programs and opinions? 

However, this analysis does not provide enought evidence to confirm the theory of the "Median Voter". 
Furthermore, our research was limited to the Switzerland's observations so this conclusion cannot be extended to the whole sample of countries. 

