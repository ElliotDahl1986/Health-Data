# Health Data 

<p align="center">
  <img width="800" src="https://user-images.githubusercontent.com/32745301/37368716-04a74420-26d5-11e8-973d-1bed9203cfd5.jpeg">
</p>


I want to explore how nation-wide county health is related to parameters we as a society are in some 
sense control of such as food, access to exercise, education, clinical care, insurance, social network 
and the presence of [Just](https://justcapital.com/2017-rankings/) companies. 

County Health Rankings & Roadmaps in a collaboration between the Robert Wood Johnson Foundation and the University of Wisconsin Population Health Institute gathered data from various sources to try to rank counties in how healthy they are. The data can be found [here](http://www.countyhealthrankings.org/explore-health-rankings/rankings-data). 

The data contains Health Outcomes which is calculated accordingly:
- Length of life (50%)
- Quality of life (50%)

The data also contains Health Factors which is calculated as such: 
- Health behaviours (30%)
- Clinical care (20%)
- Social and Economic Environment (40%)

Health behaviours, Clinical care, Social and Economic Environment is itself calculated from various parameters such as obesity, physical inactivity, primary care physician ratio, high school graduates etc. 

Ideally we would want to be able to say how the health is based on good health factors we have. We want a 1-1 relationship between these. As I show below, it is not. Health Factors is based on human evaulation of how each parameter should play into the Health Outcomes. I intend to find a better relationship using ML classifiers. 

Below is a first attempt at a very simple logistic classifier. 

I also want to incorporate how [Just](https://justcapital.com/) companies are present in the county. 

Moreover, how does the parameters we do not control play into county health, such as political views [data](https://github.com/tonmcg/County_Level_Election_Results_12-16), vicinity to nature, weather etc. I intend to find data on these various aspect and use them as well. 
