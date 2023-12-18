---
layout: default
---

In this part we will analyze the mobility change of each country during in the begeinning the year 2020 and the , which corresponds to the Covid-19 period and the first lockdown in most of the countries around the world.

# Mobility pattern
First, to be able to analyze the relationship between mobility and attention towards videogame, we need first to get the mobility data for different country.
\n
The plot below present the average mobility between the 2020-02-15 and the 2020-08-25	for France, Denmark, Germany, Italy, Netehrlands, Norway, Serbia, Sweden, South Korea, Catalonia (Barcelona), Finland and Japan. We also have differents line that present important dates of this period.   

![Branching](mobility_pattern.png)

Thus, we can see that for most of the country, the start of the lockdown was really break in the mobility pattern. Indeed, if we take France as an exmaple, the mobility decreased by around 70% after the beginning of the lockdown. However, some countries like Japan the decrease is less likely noticeable.


Therefore, if we want to see if the mobility change has an impact on the attention towards videogames, can't consider all the countries has one group but we need to group them according to thir "lockdown Intensity".

# Clustering countries

The signal of the mobility patterns is very noisy and to be able to grouped them into different cluster we can first smooth the curves by using a polynomial approximation.

![Branching](mobility_pattern_smoothed.png)

Thanks to these new smoothed curves, we can group the countries into 3 different categories of lockdown intensity: very restrictive, restrictive and unrestrictive.

![Branching](countries_cluster.png)

We can see that there are 3 clear tendancies with very similar pattern. We have that France, Italy, Serbia and Catalonia (Barcelona) have had a huge decrease in mobility.

# Attention towards video games

Now that we have grouped the countries thanks to their moblity during the Covid-19 lockdown, we can get a measure of the attention shift towards video games during the same period.

The measures we are going to use to have an insight of the population attention towards video games are wikipedia pageviews related top the same topic. During the lockdown, people were most od the time at home, and thus got more free time than usual, which translate into a higher traffic on the wikipedia website overall. That is why it is not the absolute value of the pageviews that interest us in this section, but the percentage of views on video games related pages amongst all the wikipedia traffic.

The countries with which we chose to do the analysis speak a language that is mainly speaken only in this country. This way we can assume accurately that the mobility in a certain country is linked to the views on a page written in the official language of the country. For example, we can assume that only swedish people are using wikipedia pages written in swedish.

The following figure shows therefore the percentage of wikipedia pageviews related to video games in the same countries we have in the mobility part.

![Branching](pageviews.png)
