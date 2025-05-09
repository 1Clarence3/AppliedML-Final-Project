# AppliedML-Final-Project

### Summary
We investigated which demand and supply factors most strongly influence US county-level housing price growth from 2012 to 2022 and how they vary by region. Using engineered features like income and permit counts, we trained both linear and random forest regression models with cross-validation. After finding comparable performance, we focused on the linear model to analyze how feature importance varies by region over time. Beta trends showed median income as a stronger predictor than permits, with opposite correlations to price growth. Finally, a valuation heatmap highlighted Florida, New Jersey, Washington, and Nevada as states with potentially lots of undervalued counties and a place to buy houses.


### Data
All demand data was obtained from United States Census Bureau (https://data.census.gov). The supply data (permits) was taken from this link: https://hudgis-hud.opendata.arcgis.com/datasets/HUD%3A%3Aresidential-construction-permits-by-county/about.

Reference data.ipynb for getting the datasets and formatting them to run in Model.Rmd

### Files
- 'Final_Report.pdf' is our written report for our project, with graphs and explanations
- 'Model.Rmd' is the main R code used to analyze the data, train models, and output graphs and results
- 'Final_Code.pdf' is a knitted pdf file of 'Model.Rmd' with outputs shown
- 'data.ipynb' is a preprocessing file for downloading the dataset and formatting it
