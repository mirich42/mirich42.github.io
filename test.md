# Seasonal Migration Patterns of the American White Pelican (Pelecanus erythrorhynchos)

## Species description
The American White Pelican is one of North America's largest birds, measuring from 1.4-1.8 m long with a wingspan of up to 2.4 m (Boreal Birds, 2025). When I moved to Colorado from the tropics, I was shocked to see such an instantly recognizable and iconic shorebird here along the Front Range. As it turns out, eastern populations of the American White Pelican winter along the Gulf of Mexico and migrate north in the spring to breeding grounds in the northern United States and Canada, passing right through Colorado! My biggest question was "what on earth are they eating, so far from the ocean?" This bird is a non-selective fish eater, foraging from reservoirs and wetlands along its migration route. Instead of diving for fish like the more dramatic seabirds, they will drive fish towards shore in a coordinated flock and scoop up their prey in shallow waters with their enormous bills. 

## Data description
I used two different datasets to map the migration patterns of the American White Pelican. First, I downloaded species occurrence data from the Global Biodiversity Information Facility (GBIF) from the year 2024, to limit the size of the dataset. I then downloaded ecoregion data from ArcGIS FeatureService, using the known locations of species observations from the GBIF file to inform which ecoregions I needed. 
(GBIF data citation below)

## Methods description
To make a map of observations in each month, I needed to normalize the occurrence data by sampling effort in each ecoregion and each month. Because some ecoregions are more or less populated, the data is biased towards more observations in areas with more people to do the observing. Additionally, there may be some months where people collecting data, from citizen scientitsts to birders to professionals, are out collecting data more than other months. I found the average number of occurrences for each ecoregion, and the average number of occurrences for each month. I then divided the occurrences per month in each ecoregion value by these two averages to normalize for sampling effort. 

I then made a plot of the normalized occurrences for each month of the year, check it out!

<embed type="text/html" src="img/pelican_migration.html" width="600" height = "600">
<embed type="text/html" src="img/dobbs_diner.html" width="600" height="600">

## American White Pelican Migration Plot
In the pelican migration plot you can clearly see how most American White Pelicans spend the winter months in the southern United States and Mexico and the summer months in the central United States up to central Canada. One thing that surprised me is that they do pass through the part of the United States where I grew up, around New York City. In New York spent a lot of time in the outdoors around wetlands from the spring to fall, and am surprised that I never noticed one of these very distinctive birds. It is also interesting to note that the peak times for American White Pelican observations here in Colorado appear to be April and August/September. It makes sense that they were on my mind, as I probably just saw some flying around a couple of weeks ago!

## References
https://www.borealbirds.org/bird/american-white-pelican#:~:text=American%20White%20Pelicans%20are%20gregarious,slowly%20and%20gracefully%20in%20circles.

GBIF.org (21 October 2025) GBIF Occurrence Download https://doi.org/10.15468/dl.5dzzmx

