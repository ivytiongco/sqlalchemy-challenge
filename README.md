# Project Background

Use Python and SQLAlchemy to do climate analysis and data exploration of climate database using SQLAlchemy ORM queries, Pandas, and Matplotlib, as well as designing a Flask API based on the queries developed.

## Files contained in this repo

* Jupyter notebook "climate.ipynb" contains analysis for the following:
   * Step 1 - Climate Analysis and Exploration
       * Precipitation Analysis
       * Station Analysis   
   * Bonus 
       * Temperature Analysis I
       * Temperature Analysis II
       * Daily Rainfall Average (partial analysis)
* Python file "app.py" is used to create Flask API for:
   * Step 2 - Climate App 
* SQLite file "hawaii.sqlite" is included in this repo and was used in the jupyter notebook.

## Bonus - Temperature Analysis I - Question
Use the t-test to determine whether the difference in the means, if any, is statistically significant. Will you use a paired t-test, or an unpaired t-test? Why?
* I chose to use an unpaired (independent) t-test because weather data in different months is independent of each other.
* The p-value of 0.00036573 resulting from this t-test indicates that we can reject the null hypothesis that the average temperature in June is the same as the average temperature in December at all stations across all years in the dataset. Thus, the difference in the means is statistically significant.


