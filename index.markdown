---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# page does not show the posts folder
layout: page
title: "Burglaries during COVID-19: The Curious Case of San Francisco"

---


Perched on the edge of the California coast, San Francisco is a city of contrasts; tech giants meet glamorous Victorian streets while yoga studios stand near graffiti-tagged alleys. These contrasts inherently bring with them a cultural diversity crammed into 10 districts that feel undeniably captivating.

But suddenly, 2020 happened, and with it, COVID-19, now ranked among the world’s deadliest epidemics, took place. 

COVID-19. The infamous pandemic that knocked everybody up. It swept through the world and brought every big city to a standstill, and San Francisco wasn’t an exception. Streets emptied. Offices shut down. People suddenly faced an obliged lockdown. In a city known for its non-stop rush, stillness became the new normal. And with this stillness, burglary, like many other crimes, began to shift up in surprising ways. 

Burglary is the illegal entry of a building with the intent to commit a crime. Burglary doesn’t happen in broad daylight or under dramatic headlines. It happens quietly, behind closed doors, in homes, apartments, and even businesses. Over the past two decades, burglary has taken on new patterns as the city has evolved and with the pandemic even more. 

This story unpacks how burglary affected the city of San Francisco during this global crisis, which districts saw the most break-ins, how the time of day affected these behaviors and an analysis of the trends that arose in such a non-expected situation for everybody. 

In this project, you'll be immersed in a deep dive into San Francisco’s burglary patterns during one of the most unusual years in recent history: 2020.

Using publicly available data from the San Francisco Police Department, we analyzed over 20 years of crime reports, from 2003 to the present. This rich dataset includes more than 2 million reported incidents, ranging from thefts and assaults to vandalism and vehicle break-ins.

With city streets emptied and routines stopped, we asked ourselves: How did this disruption affect burglary trends across San Francisco?

We filtered and visualized the data with one goal in mind:
To understand how burglary patterns were shaped by the COVID-19 crisis and what these shifts reveal about the changing situation of the city. 

# Before and After: Two Decades of Burglary in San Francisco

To understand how burglary has evolved in San Francisco, we began by zooming out, way out. The chart below shows burglary incidents from 2003 to early 2024, giving us a long-term view of the city’s situation when it comes to break-ins.

<figure class="figure-wrapper">
  <img src="/assets/images/output.png" alt="Crime pattern visualization">
  <figcaption class="figure-caption">Figure 1: Spatial distribution of burglary cases in San Francisco during COVID-19 lockdown periods</figcaption>
</figure>

### Here’s what stands out from Figure 1:

In the early 2000s, burglary cases were relatively high, peaking around 2005 with over 7,000 reported burglaries. A notable decline followed from 2007 to 2011, coinciding with the 2008 Great Recession. This remains a rare case; instead of crime increasing, as is often expected during economic crises, crime continued to decline. According to the Stanford Center on Poverty and Inequality, crime rates across the U.S. kept falling during this period, but at a slower pace.

After 2012, San Francisco entered a period of relative stability, with burglary hovering between 5,800 and 6,200 cases annually, until 2020.

### Then, the pandemic spiked. COVID-19 took over the world.

With COVID-19, a drastic shift arose. Burglary spiked dramatically, peaking in 2020 with over 9,000 reported incidents, the highest in two decades. But this wasn’t due to a sensational rise in criminal behavior. Instead, it reflected a deeper transformation of the city’s social and economic structure.

Lockdowns, shutdown businesses, empty streets, police departments shifted focus, and many establishments left unoccupied created the ideal conditions for opportunistic burglary. At the same time, job losses, housing insecurity, and a widening wealth gap intensified pressure on vulnerable populations. These stressors, according to the article Crime and deviance during the COVID-19 pandemic [2], are key drivers of property crime, especially during unstable periods.

The spike in burglary during 2020 reflects how fragile urban systems become under crisis.

### A gradual decline – But not a return to “Normal”

Since then, burglary rates have gradually declined but remain above pre-pandemic levels. 

# Burglary Distribution Across San Francisco’s Districts in 2020

<!-- <figure class="figure-wrapper">
  <img src="/assets/images/map.png" alt="Crime pattern visualization">
  <figcaption class="figure-caption">Figure 2: District distribution of burglary cases in San Francisco during COVID-19 lockdown periods</figcaption>
</figure> -->

<figure class="figure-wrapper">
  <iframe src="/assets/images/sf_burglary_map.html" width="1000" height="800" frameborder="0"></iframe>
  <figcaption class="figure-caption">Figure 2: District distribution of burglary cases in San Francisco during COVID-19 lockdown periods</figcaption>
</figure>

As shown in the previous graph, 2020 recorded the highest number of burglaries in San Francisco. But where exactly did these crimes occur? San Francisco is divided into 10 police districts: Bayview, Central, Ingleside, Mission, Northern, Park, Richmond, Southern, Taraval, and Tenderloin. This analysis focuses on how burglaries were distributed across these neighborhoods on Figure 2.

### Socioeconomic Status and Burglary Trends

Burglary rates in relation to the socioeconomic status reveal an interesting trend. The Northern district, home to some of the wealthiest neighborhoods, experienced the highest number of burglaries. In this area, between 20% and over 40% of households reported annual incomes exceeding $200K [3]. In contrast, the Tenderloin district, where only 6.5% of households earn over $200K, had the lowest burglary rate [3].  This pattern suggests a correlation between wealth and burglary frequency, with wealthier neighborhoods experiencing higher rates.

A similar trend emerges for education levels, which often reflect socioeconomic status. In the Northern district, 60% to 80% of residents hold a bachelor’s degree or higher, compared to just 36% in Tenderloin [3]. While education may not directly influence burglary rates, it reinforces the relationship between wealth and crime patterns.

### Challenging Common Assumptions

You may think that burglaries would be more common in low-income areas or areas with lower levels of formal education, while wealthier neighborhoods would have a greater investment in security measures [4].

However, the data contradicts these assumptions, burglaries were more common in wealthier areas. Interestingly during the pandemic, lower-income neighborhoods with lower education levels residents had a lower probability of experiencing burglaries. 

### Future Research Directions

To gain deeper insights into these trends, a follow-up study comparing burglary patterns before, during, and after the pandemic would be valuable. Analyzing whether burglary rates have since returned to pre-pandemic levels or if new long-term patterns have emerged could help clarify the factors influencing these shifts.

# Burglary Hourly Trends During the Pandemic.

Most burglaries occur in broad daylight, contrary to the common assumption that they happen at night [5]. However, did this trend hold during the pandemic? In this section,  burglary hourly patterns in different districts are analyzed.

<!-- <figure class="figure-wrapper">
  <img src="/assets/images/interactive.png" alt="Crimes per hour of the day in 2020">
  <figcaption class="figure-caption">Figure 2: District distribution of burglary cases in San Francisco during COVID-19 lockdown periods</figcaption>
</figure> -->

<figure class="figure-wrapper">
  <iframe src="/assets/images/burglary_by_hour.html" width="800" height="600" frameborder="0"></iframe>
  <figcaption class="figure-caption">Figure 3: Interactive visualization of burglary crimes by hour of day across different districts in San Francisco (2020). Click on district names in the legend to show/hide them.</figcaption>
</figure>

### Northern District: The Most Burglarized Area

Northern district shows a distinct pattern. Most burglaries occurred between midnight and 6 AM, then gradually declined until noon. A minor increase was observed during the early afternoon (12 PM to 2 PM), while the safest hours, when burglaries were least frequent,  were between 3 PM and midnight. This contrasts with the usual pattern suggesting that burglaries are more common in daylight.

Mission, Central, and Southern which had elevated burglary levels but not as high as Northern, followed a similar trend. Interestingly, each district experienced a noticeable surge in burglaries between 12 PM and 1 PM.

### Tenderloin: The Safest District from Burglaries

In Tenderloin, the trend remained consistent with most crimes occurring between midnight and 3 AM. A sporadic spike was observed between 12 PM and 2 PM. Overall, the safest hours were from 3 PM to midnight.

### Bayview: A Departure from the Nighttime Trend

Despite having a relatively low burglary rate, Bayview followed a different pattern. The highest burglary rates occurred between 5 AM and 6 AM and from 11 AM to 6 PM. This aligns with burglaries being more common during daylight hours.

### Mixed Patterns

•	Richmond: Most burglaries occurred between midnight and 3 AM, with additional spikes at 8 AM and 10 PM. The safest hours were in the afternoon.

•	Park: The district saw an increase in burglaries between 7 AM and 8 AM, as well as a more prolonged period of activity between 8 AM and 1 PM.

•	Ingleside: Burglaries peaked between 4 AM and 6 AM, but overall, incidents were more evenly distributed throughout the day

### Takeaways

While burglary patterns during the pandemic varied across districts, a general shift toward nighttime crime is evident, contradicting the usual trend of daytime burglaries. However, certain areas,, still followed the expected daylight pattern. These insights suggest that external factors may have influenced criminal behavior during this period.

# References 

[1] Uggen, C. (2012). Crime and the Great Recession. Stanford Center on Poverty and Inequality. https://inequality.stanford.edu/sites/default/files/Crime_fact_sheet.pdf


[2] Regalado, J., Timmer, A., & Jawaid, A. (2022). Crime and deviance during the COVID-19 pandemic. Sociology Compass, 16(4), e12974. https://doi.org/10.1111/soc4.12974


[3] The San Francisco Standard. (2022, December 8). San Francisco neighborhood maps show new census data. https://sfstandard.com/2022/12/08/san-francisco-neighborhood-new-census-data-maps/


[4] Walden University. (n.d.). What influences criminal behavior? Walden University. https://www.waldenu.edu/online-bachelors-programs/bs-in-criminal-justice/resource/what-influences-criminal-behavior


[5] Safewise. (n.d.). 8 surprising home burglary statistics. Safewise. https://www.safewise.com/blog/8-surprising-home-burglary-statistics/#Sources

# Contributions 

Page set up - s250202
Story development - s250273 & S250221
Introduction & Visualization 1 - s250202 & 250221
Visualization 2 & 3 - s250273 & s250202





---