# Starbucks Reserve Roastery Expansion Project

## Project Overview

Assumming I'm a Starbucks Big Data Analyst, the goal of this project is to identify potential locations for the next Starbucks Reserve Roastery in California. The Reserve Roasteries are larger establishments with unique features, including various food and wine options, along with upscale lounge areas. The project involves investigating the demographics of various counties in California to determine suitable locations.

## Data Sources and Geocoding

We utilized Starbucks store location data and demographic information for counties in California from **Kaggle**. Geocoding was performed using Nominatim to fill in missing store locations based on their addresses.

## County Selection Criteria

### Mandatory Criteria:
1. **Households Making $150,000 or More:**
   - Counties with at least 100,000 households making $150,000 per year.

2. **Median Age:**
   - Counties with a median age less than 38.5.

3. **Inhabitant Density:**
   - Counties with a density of at least 285 inhabitants per square kilometer.

### Additional Criteria (At least one of the following):
1. **Households Making $150,000 or More:**
   - Counties with at least 500,000 households making $150,000 per year.

2. **Median Age:**
   - Counties with a median age less than 35.5.

3. **Inhabitant Density:**
   - Counties with a density of at least 1400 inhabitants per square kilometer.

These criteria aim to identify counties with a favorable demographic profile for the establishment of a Starbucks Reserve Roastery.

## Identified Store Locations

Successfully identified a total of 1043 potential Starbucks store locations across the selected counties. The distribution of stores is as follows:

- Los Angeles: 667 stores.
- San Diego: 289 stores.
- San Francisco: 87 stores.

## Conclusion and Recommendations

Considering the criteria and insights gained from the analysis, the following counties stand out as promising for the next Starbucks Reserve Roastery location:

1. Los Angeles
2. San Diego
3. San Francisco

Further analysis and on-site evaluations are recommended to make a final decision based on specific location features and local factors.

For a detailed walkthrough of the analyses and visualizations, explore the Jupyter Notebook in this repository.

