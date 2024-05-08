# LEJOG: Exploratory Data Analysis of Lands End to John O'Groats Walk

Welcome to the LEJOG (Lands End to John O'Groats) exploratory data analysis project repository! 
This project aims to analyze my journey from Lands End to John O'Groats, one 
of the most iconic routes in the United Kingdom and the traditional "End to 
End" journey. 

Land's End in Cornwall is at the South-West tip of England while John O'Groats 
lies up in the far North-East of Scotland. As the crow flies, the distance 
between the two is around 603 miles, however walking inevitably involves a 
much greater distance (e.g. to avoid the sea!) and in particular, my journey 
as documented here totalled around 1300 miles or 2200km. 

## Interactive Route Plot
Before delving into the details of the analysis, you can explore an 
interactive plot of the route on my website at [emmaklofthouse.com/end2end](http://emmaklofthouse.com/end2end).

![Screenshot_map](https://github.com/EmmaKLofthouse/LEJOG/assets/18194748/697d1c2d-4eab-40c4-adfe-64aa24038de2)

## Dataset
The data used here was personally recorded as I was walking. It consists of two tables: 1. overview.csv which includes the day, date, start and end locations, distances walked and 2. counts.csv which includes various things that I kept track of along the way such as steps, weather, number of stiles, number of dogs/cats I petted, county borders and how many times I was chased by cows!

## Project Overview

The lejog.ipynb notebook included in this repo contains the cleaning of the data, creation of the interactive map above and various analyses of which I include a few below as examples. 

### Analysis of Walking and Rest Days

I averaged in the region of 20-25km a day.
![days_distance](https://github.com/EmmaKLofthouse/LEJOG/assets/18194748/ccb9f3c7-f1f4-45e6-8dcf-e7ec434976dd)

I walked more during the week, mainly because when I took rest days, they were more likely to be at the weekends so that I could see family and friends.

![avg_distance](https://github.com/EmmaKLofthouse/LEJOG/assets/18194748/1ac8738f-b781-4cb4-bef1-c3363c2cba26)


### Daily Progress Towards John O'Groats
 Tracking the progress made towards the final destination over time. We see that at various points I was getting making little progress towards John O'Groats or moving further away.. This was an intentional choice! In particular when I wanted to reach the Southern/Northern most points or when I chose to head west from Edinburgh in order to pick up some of the nice long-distance footpaths (West Highland Way, Great Glen Way).
 
![Distance_to_JOG](https://github.com/EmmaKLofthouse/LEJOG/assets/18194748/b694551d-de81-433e-89b3-94d86dae39a5)


### Correlation Analysis
 Investigating correlations between various factors such as weather conditions, animals encountered, and daily distances walked.

![corr](https://github.com/EmmaKLofthouse/LEJOG/assets/18194748/76236b86-87ba-463d-8163-8bc2d3c5acda)

There is obviously a very strong correlation between distance walked and steps but also some other weaker but interesting correlations. For example, cow encounters and stiles (both are associated with farms and fields), more dogs petted on sunnier days and also... the number of times I cried is positvely associated with cow encounters. This makes sense when you know that despite my love of hiking I have a strong fear of cows and did get chased a few times!


## Usage

To replicate the analysis or explore the code further:

1. Clone this repository to your local machine.
```
git clone https://github.com/EmmaKLofthouse/LEJOG.git
```
2. Execute the Jupyter notebooks provided in the analysis directory to view the data cleaning, visualization, and analysis processes.

## Contributions

Contributions to this project are welcome! If you have ideas for improvements or would like to add new analyses, feel free to submit a pull 
request. Any questions about the route or my experience are also very welcome!
