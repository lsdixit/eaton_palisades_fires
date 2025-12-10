# Environmental Justice Impacts of Fires using False Color Imagery and Landsat data
Repository housing code and outputs for the blog post investigating the impacts of the Eaton and Palisades fires in Los Angeles, CA.
The final blog post is housed on [Leela Dixit's Website](https://lsdixit.github.io/posts/2025-12-1-fire-analysis/220_blog_post(1).html).

# Background
The Eaton and Palisades fires in Los Angeles County were devastating for local communities, damaging thousands of homes and many acres of ecological habitat, leaving deep scars in both the communities they affected and the land itself. In this study, we will visualize the extents and impacts of the Eaton and Palisades fires using false color imagery through Landsat data and known perimeters of both fires, and focus in on an environmental justice metric to assess the community's potential response to wildfire.

## Analysis Highlights

In this study, we will highlight the following skills:

1.  Examining rioxarrays and NetCDF files to pull, transform, and manipulate spatial data.
2.  Map true and false color images from NetCDF files.
3.  Map census tracts that intersect the Eaton and Palisades fires to explore potential injustices.

# Data
Landsat data are from [Microsoft Planetary Computer data catalogue](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2). These data contain bands for red, green, blue, near-infrared and shortwave infrared, from the Landsat Collection 2 Level-2 collected by Landsat-8. Our data is cropped to areas surrounding the extent of the fires.

Perimeter data are from [Los Angeles County Dissolved Fire Perimeter Data](https://geohub.lacity.org/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about). These data originate from data containing daily snapshots of perimeters, but are dissolved into one layer for these data.

Fire perimeter data: https://geohub.lacity.org/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about Landsat data: https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2

EJI data are from the [Environmental Justice Index (EJI)](https://www.atsdr.cdc.gov/place-health/php/eji/eji-data-download.html), a national tool to measure environmental burden. The EJI ranks tracts for 36 different factors developed from data from many different sources.

# Content
```bash 
eaton_palisades_fires repository
│   README.md: contains README code.
│   220_blog_post.ipnyb: The blog post final code and output.
│   220_blog_post.ipnyb: The blog post final code and output.
│   220_blog_post.ipnyb: The blog post final code and output.
Data are not pushed to github, this is the recommended file structure:
│   .gitignore
│   └── data folder
        │   perimeter shapefiles
        │   Landsat netcdf file
        │   EJI geodatabase
```

# References
Microsoft Planetary Computer. (2024). Microsoft.com. https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2
‌Palisades and Eaton Dissolved Fire Perimeters (2025). (2025). Lacity.org. https://geohub.lacity.org/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about
CDC. (2024, December 3). EJI Data Download. Place and Health - Geospatial Research, Analysis, and Services Program (GRASP). https://www.atsdr.cdc.gov/place-health/php/eji/eji-data-download.html

# Acknowledgments
This work was done by Leela Dixit, with support from Carmen Galaz García, Annie Adams, and classmates from the MEDS [EDS 220](https://bren.ucsb.edu/courses/eds-220) UCSB course.


‌



