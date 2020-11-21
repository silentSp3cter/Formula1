# Formula 1 Data Analysis

The purpose of this project is to analyze and exxplore various data points in Formula 1. I also tried to build a model to predict whether a driver will finish in the Podiums or not


## Data Collection

Files : `API_data`

For my data mining I used the [Ergast F1](https://ergast.com/mrd/) data repository, which contain information about all the championships and races from 
1950 till date.
Eventually I combined all the data about races, results, drivers and constructors standing positions, 
qualifications and weather into a single dataframe.


## EDA

Files : `f1_analysis`

### How have lap speeds evolved over the last 10 years?

During qualification sessions the drivers try to set their fastest time around the track and the grid position
is determined by the drivers' best single lap, with the fastest on pole position. Starting on pole position is crucial
in those circuits where overtaking is more difficult, in addition to having the advantage of staring a few meters ahead
and on the normal racing line, which is usually cleaner and has more grip. The following graph shows the correlation between
staring in pole position and winning the race in some of the most popular circuits.

![](images/lap_speed.png)
