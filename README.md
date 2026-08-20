# Global Urban Air Quality and Pollution Analysis
Analysis of pollution levels in the top 50 most populated industrial cities in the world, conducted as part of my data science apprenticeship.

## Overview
- **Objective**: To identify concerning trends in the past 12 months of urban air quality data, with a particular focus on pollutants known to pose significant risks to respiratory health.
- **Dataset**: Kaggle (https://www.kaggle.com/datasets/iconicwasil/global-urban-air-quality-and-pollution-time-series/code)
- **Methods**: EDA, OLS regression modelling.
- **Results**: Riyadh has not only experienced the highest levels of pollutants sourced primarily from vehicle exhaust and smog and it is also presenting the largest upward trend in the pollutant of interest in the past 12 months.

## Technical Details
- **Languages**: Python.
- **Libraries**: pandas, seaborn, matplotlib, SciPy.
- **Tools**: Jupyter.
  
## How to Run
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run the main notebook

## Key Findings
- The final results appear to show that Riyadh has not only experienced the highest levels of pollutants sourced primarily from vehicle exhaust and smog, ahead of Shanghai and Beijing, but it is also presenting the largest upward trend in this pollutant level in the past 12 months.
- Visual analysis of scatterplots presents clear seasonal trends across most of these cities, where these pollutant levels appear to rise during colder months, but Riyadh presents consistently high levels with these pollutants spiking in both winter and summer.
- In contrast, Jakarta presents the largest statistically significant downward trend among the cities present here. Jakarta presents consistent pollutant levels throughout the 12-month period without sign of seasonality. This result would benefit from further analysis to understand why these changes might be occurring.

## Future Work
- Pull together a larger dataset spanning multiple years to explore seasonality within each urban environment.
- Explore more advanced analysis techniques that summarise multiple pollutant types across all cities at once.

## Contact
Pierce Coveney | www.linkedin.com/in/piercecoveney | pierce.coveney@my.bpp.com - piercecoveney@gmail.com
