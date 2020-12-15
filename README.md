# Readme is Work in Progress. However, code is complete. Refer `f1_analysis.ipynb`

# Formula 1 Data Analysis

The purpose of this project is to analyze and explore various data points in Formula 1. I also tried to build a model to predict whether a driver will finish in the podiums or not.

## Data Collection
Initially, I had found this dataset on the popular data science community Kaggle. Then I found that this was in turn taken from the Ergast website. Since, the datasets on kaggle were quite outdated, I downloaded all the datasets from Ergast. Ergast has the option to use it's API to gather the data, but I found it easier to download all the data and use it.

The dataset had multiple .CSV files with each containing primary keys to allow for merging the data. The files that originally came with the data set are:

Dataset Files:

`circuits.csv`
`constructor_results.csv`
`constructor_standings.csv`
`constructors.csv`
`driver_standings.csv`
`drivers.csv`
`lap_times.csv`
`pit_stops.csv`
`qualifying.csv`
`races.csv`
`results.csv`
`seasons.csv`
`status.csv`

All the files were merged to create a final data frame called: `final_data.csv`

## EDA

Files : `f1_analysis`

### Worldwide circuit distribution.

We see most of the circuits are concentrated in Europe, followed by America.

![](Images/circuit_world.png)

### Most hosted Grand Prixs?

The British and Itaian GPs have been hosted the most with a tally of 71 each.

![](Images/grandprix.png)

### Most dangerous circuits?

Of course it is Monaco. With Monaco being a steet circuit, it has seen a lot of incidents. Surprisingly, Silverstone also has a fairly high record of incidents. Could be due to the fact that it has hosted the most number of GPs till date and the numbers have piled up over the years. It's not surprising to see that Monza (The temple of Speed) has seen so many incidents.

![](Images/dangerous_circuits.png)

### The fastest circuits?

The temple of Speed (Monza) is no doubt the one with the highest average top speeds. However, Spa-Francorchamps and Silverstone are not that far behind. Monaco and Marina Bay have the slowest speeds. After all they are street circuits with very tight corners.

![](Images/fastest_circuits.png)


### How have lap speeds evolved over the last 10 years?

We can see that the lap speeds have obviously seen a steady increase over the last 10 years. However, we see that post 2014, the average speeds have risen faster per year post the 1.6 V6 Turbo Engine rule change.

![](Images/fspeeds_10y.png)

### Some of the shortest circuits - Evident by the fast lap times.

Red Bull ring, Jose Carlos (This is shorter than the red bull ring, but the average speeds in the red bull ring are quite high), Hockenheimring. 

![](Images/shortest_circuits.png)

### Lap times over the past 10 years.

![](Images/laptimes_10y.png)

### Pit Stops

Unfortunately, we do not have pit stop information before 2011, hence, we are limited to the data points only after then. Looking at the charts, we see that the average stop time has actually gone higher up. This could be due to the pit lane speed limits. Earlier the speed limits were higher than today, hence resulting in shorter pit times. Please note, the pit time is inclusive of the stationary time and the time the car is in the pit lane.

![](Images/stoptime_10y.png)

### Number of Stops

Most circuits follow the 2-stop or 1-stop strategy. But this varies widely, depending on the weather, any incidents on track, etc.

![](Images/no_stops_circuit.png)

![](Images/cuircuit_stopTimes.png)
