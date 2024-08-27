# Over the Years, a Climate Storytelling 2075 Project

## Final Artwork
![A digital self portrait, overlaid with a series of colored lines depicting sea level rise and a timelapse of sea level rise over a satellite image.](https://github.com/via-zhang/climate-storytelling/blob/main/artwork/Over_the_Years.gif)
"Over the Years" is a multimedia artwork that explores data visualization as an avenue for climate storytelling. Inspired by the role of location: how we interact with each other, with our histories, and with our environment, this artwork features a timelapse of projected sea level rise in the Everglades in South Florida, a line graph of sea level change off the coast of Southeast Florida since 1994, overlaid with a personal portrait. Accompanying these visuals is a short poem that delves into my emotions regarding the escalating climate crisis.

## Poem
```
over the years
I can feel
the thrashing
in my heartbeat
as veins of
seagrass unfurl
against the ocean's
restless rise
we know we must
rise higher
```
I wrote this poem, which appears in the final artwork line by line, in reflection of my fear and hope surrounding the climate crisis. I often feel overwhelmed by the vast changes that are happening and how communities are being impacted by climate change — yet I strongly believe in the power of communities to come together and create equitable, sustainable solutions.

# Data

## Sea Level Change
Visualizing local sea level data from the [NOAA tide-monitoring station](https://tidesandcurrents.noaa.gov/stations.html) at Virginia Key, Florida, near my home in Southeast Florida. More information is available at the [CO-OPS Relative Sea Level Trends Tool](https://www.climate.gov/news-features/features/interactive-map-how-has-local-sea-level-united-states-changed-over-time).

<p align="center">
  <img src="https://github.com/via-zhang/climate-storytelling/blob/main/sea-level-change/graphs/mean_sea_level_8723214_grid.png" alt="Graph showing sea level change from 1994 to 2023 for Virginia Key, Florida, with one line for each year. There is an upward trend in the lines, indicating sea level rise." width="500">
</p>

The graph shows sea level change (relative to the mean sea level from 1983–2001) in Virginia Key, Florida for each month from 1994 to 2023. The color indicates the year: darker colors indicate more recent sea levels up to 2023, and ligher colors indicate sea levels closer to 1994. There is a prominent rise in sea level for the observed region (Virginia Key, Florida), and similar trends of sea level rise is seen in many other regions.

## Projected Sea Level Rise
Visualizing projected flooding from sea level rise (of 0 feet to 10 feet above average high tides in increments of 0.5 feet). The sea level depth data is from the [NOAA Office for Coastal Management's (OCM) Sea Level Rise Viewer](https://coast.noaa.gov/digitalcoast/tools/slr.html). The different colors represent depth in meters above ground for the projected sea level rise, with darker blue indicating the sea level is higher above ground, and lighter blue indicating the sea level is at ground level.

<p align="center">
  <img src="https://github.com/via-zhang/climate-storytelling/blob/main/sea-level-projection/fl_se_slr_depth_timelapse.gif" alt="Timelapse showing projected flooding from sea level rise of 0 feet to 10 feet for a region in South Florida." width="500">
</p>

The figure above shows the region included in the final artwork, a part of the Everglades in South Florida. The [state boundary lines](https://www.arcgis.com/home/item.html?id=774019f31f8549c39b5c72f149bbe74e) are from the U.S. Census Bureau provided by Esri. The satellite image is a composite Sentinel-2 image from March to May 2024 downloaded using the `rsi` package in R developed by Michael Mahoney.

