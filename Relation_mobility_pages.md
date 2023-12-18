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
\n 
Therefore, if we want to see if the mobility change has an impact on the attention towards videogames, can't consider all the countries has one group but we need to group them according to thir "lockdown Intensity".

# Clustering countries

The signal of the mobility patterns is very noisy and to be able to grouped them into different cluster we can first smooth the curves by using a polynomial approximation.

![Branching](mobility_pattern_smoothed.png)
