# Rent price analysis in Budapest

Welcome!

In last couple of years (2015-2020) rental listings in Budapest became YTD more and more expensive, and, due to my curious nature, I wanted to understand why.
This project aims to quantify the effects of housing variables (e.g. condition, is it furnished) to the price of the listing in Budapest.

## What to know

This project is completely written in __python__, but I also used __powerBI__ for my data vizualizations and I created my own __geojson__ for the data mapping using folium.

### Project parts

- Webscraping
- Change Data Capture
- Loading data to DB2 database
- Data analysis
  - data cleaning
  - outlier detection & handling
  - null handling
  - descriptive statistics
  - model building
    - linear regression
    - regularized regression (lasso & ridge)
