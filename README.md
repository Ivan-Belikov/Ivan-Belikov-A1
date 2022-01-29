# Ivan-Belikov-A1

<img width="554" alt="image" src="https://user-images.githubusercontent.com/98556759/151647678-f4ec54b3-fb5a-4508-95cb-a87cb9391db1.png">

For my graph, using the given 1900 and 2000 Census data, I wanted to answer the question: “Has the male and female population diverged?” In order to answer this 
question, I decided to build a multi line chart to show a change over time, since we are plotting discrete categorical data, age groups, and continuous metric data, 
population. Moreover, a multi line chart would also be an effective visualization because of the need to compare two forms of quantitative data, population and age, in order 
to answer this question. To effectively answer this question with my visualization, I plotted a total of four lines: male population in 1900, female population in 1900, male 
population in 2000, and female population in 2000 across the age groups. In reading the visualization, it’s important to remember that the visualization only shows how many 
people were in a certain age group at that current year, which in this case is 1900 and 2000. The visualization does not give any implications on life expectancy or the 
health of men and women in 1900 and 2000. 

I picked this question in particular because after observing the data I noticed that there was a significantly larger gap between the male and female population of 70 
year olds and older in 2000 compared to the male and female population of 70 year olds and older in 1900. I wanted to visualize and highlight this part of the data to 
possibly gain a better understanding of it. Before doing so, I had to manipulate and filter the given census CSV data down to only the columns I needed: population, sex, age, 
and year. I then had to separate the data and group them into smaller subsets for each line on the graph. Therefore, the subsets of the data I created were a subset for male 
population in 1900, female population in 1900, male population in 2000, and female population in 2000. Each subset of the data included age group and its respective 
population size for that gender and year. 
	
In designing my visualization, I went back and forth a lot concerning what design decisions I'd make to accurately highlight and convey the insights gained from my 
visualization. Originally, I planned to differentiate the male and female lines of my graph with color, making the male line blue and female line pink. Upon further thought, 
I decided against this design decision for two reasons. Although it would distinguish male from female, it would not highlight any important additional insights and 
colorblind viewers may not be able to distinguish this as easily, which may convey wrong insights. Additionally, the blue and pink lines may be hard to distinguish apart from 
one another around parts that they overlap, especially for the set of lines plotting population data in 1900. Therefore, I decided to make the male lines solid and female 
lines dashed, addressing this difference in the legend. This design decision would allow the viewer to more easily distinguish between the two lines without making any extra 
unnecessary design decisions that wouldn’t offer any helpful supporting information about the data. Moreover, I decided to truncate the values to a singular whole number on 
the y-axis showing population count for readability purposes. This would make it easier for the viewer to read the values and save space from being unnecessarily used up by 
digit heavy numbers in the millions. I accounted for this truncation of values in the label of the y-axis, informing the viewer that all values on the y-axis are in millions 
(2 = 2,000,000). Lastly, because I wanted to show the divergence of the male and female population in 2000 compared to 1900, I labeled the set of lines plotting the 2000 data 
and the set of lines plotting the 1900 data. In doing so, I am able to highlight to the viewer not only the difference in population size in 1900 and 2000 but also the 
significant divergence the male and female population had in 2000 compared to 1900 for men and women aged 70 and older. By labeling the two sets of lines, the viewer can 
immediately see that in 1900 the male and female populations were for the most part almost exactly equal to each other across all age groups and had a downward trend as 
expected, but the male and female population in 2000 had a sudden upward trend in population size for people aged 30-45 years old and had a major divergence in population 
size between males and females born from 1910-1930. 

From my data visualization, one of the first anomalies you can immediately see is the divergence between the male and female population in 2000 between the ages 70 to 
90, which seemingly never happens in any of the age groups in the 1900 census data. So what’s up with this sudden gap in population? After some research, I theorize that this 
sudden “missing male population” is due to males who served in WW2. According to the graph, the gap occurs around age 70 and continues onwards. Males ages 70 to 90 in 2000 
would have been born around 1910 to 1930, meaning that they would have been around the age of legal enlistment during WW2, although there were plenty of illegal enlistments 
as well. According to historical accounts, after the war, “many war veterans were left to cope with long-term physical and mental medical conditions”, such as tuberculosis 
and shell shock. I believe that these lasting long term effects on the physical and mental health of male WW2 veterans could have contributed to their earlier deaths, 
compared to their female counterparts. Furthermore, you can also see a second anomaly in the visualization in the 2000 data around the ages 30 to 45. You can clearly see that 
there is a sudden upward trend in population size, which you likely wouldn’t expect as you move towards the older age groups. Again, a possible explanation for this sudden 
upward trend could be due to the effects of the end of WW2. During WW2 and the Great Depression, many people decided to hold off on starting a family due to current 
conditions. Afterwards, people believed that it was a safe and good time to start the family they had always wanted, giving birth to the baby boomer generation and a massive 
spike in population. According to the graph, people aged 30 to 45 would have been born around the 1950’s and 1960’s, which was roughly the time of the baby boomer generation. 
According to historical data, “By 1964, Boomers comprised 40% of the US population”. Therefore, I believe that the birth of the baby boomer generation after WW2 could be a 
possible explanation for the sudden upward trend in male and female population size aged 30 to 45 in the 2000 census data. 

Sources:
https://www.sciencemuseum.org.uk/objects-and-stories/medicine/medicine-aftermath-war
https://www.generations.com/insights/baby-boomer-101
