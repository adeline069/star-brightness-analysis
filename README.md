# Star Brightness Analysis — HYG Database

Analysis of stellar data from the HYG database (Hipparcos, Yale, 
Gliese catalogs) to compute and visualize the absolute brightness 
of stars.

## Dataset
- Source: HYG Star Database (astronexus.com)
- Features: star name, constellation, apparent magnitude, distance, 
  spectral type, color index, luminosity

## What I did
- Cleaned and filtered the dataset (removed duplicates and invalid 
  distance values) using pandas
- Implemented the Pogson equation to calculate absolute magnitude 
  for each star
- Computed a Kendall correlation matrix across all numerical features
- Created a Color-Magnitude Diagram (Hertzsprung-Russell Diagram) 
  to visualize the relationship between star color and brightness

## Key finding
Luminosity shows the strongest correlation with absolute magnitude, 
confirming known astrophysical relationships.

## Tools
Python · pandas · NumPy · matplotlib · Jupyter Notebook
