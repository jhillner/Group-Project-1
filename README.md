# Team Numpy
#### The objective of Team Numpy's project was to evaluate productivity of nuclear-generated power in the US. We also aimed to determine how the population densities around US nuclear reactors has evolved over the past 50 years. 

##### Our final project proposal can found be  <a href="https://docs.google.com/document/d/11eoavZTTPMZYcqoTUWlJLavqZMRizLxF-9CeZdN2amA/edit">here.</a>

##### Our final project slides can found be  <a href="https://docs.google.com/presentation/d/1D4UDGq6WI7Nqu6KepLMrIiF2H7tKGteYR_cWN_Di18A/edit#slide=id.p">here.</a>

#### We found the following webistes useful for gathering data:
<ul>
    <li><a href="https://www.kaggle.com/census/us-population-by-zip-code">Kaggle Zip Census Data</a></li>
    <li><a href="https://www.census.gov/data/tables/time-series/demo/popest/2010s-total-cities-and-towns.html">US Census Data</a></li>
     <li><a href="https://www.kaggle.com/marchman/geo-nuclear-data">GeoNuclearPower</a></li>
     <li><a href="https://public.opendatasoft.com/explore/dataset/us-zip-code-latitude-and-longitude/table/">Coordinates of US Zip Code</a></li>
     <li><a href="https://en.wikipedia.org/wiki/Nuclear_power_in_the_United_States">Nuclear power plants in US</a></li>
</ul>


#### We wrote several scripts and can be found in our Git Repo under "Code". A few noteables include:
<ul> 
<li> <b><em>popNukeHeatMap.ipynb</em></b> This script plots the location of all active reactors, as of 2010. Population densities within 500 km are plotted as heatmaps. </li>
<li> <b><em>plantPop.jpynb</em></b> This script merges nuclear reactor location data with population data (according to zip code). The populations are binned in 10km bins and then plotted as a function of distance from reactors. The plots are restricted to population densities within 500km of each reactor. </li>







