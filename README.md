# Temperature Visualization
This project shows the temperature variation over the years from 2004 through 2015.

### File read-in
The files given are temperature.csv and binsize.csv having  the size of (165085, 4) and (18259, 15) respectively.


### Data Quality checks
Intial data quality checks are performed in both the datasets after read-in.
No dulpicates and missing values where found in temperature data.
Some states where found to be missing in bin data however that doesnt affect significantly in our analysis.
### Feature Engineering
Some essential feature engineering is applied to the data like transforming the date variable to datetime
The data is filtered to required range from 2005 to 2014
And the factor of leap year is identified and removed in this section
### Logic applied
  The code extracts record highs/lows from past years.
  It computes 2015’s highs/lows separately and  aligns indices to allow comparison.
  It identifies record-breaking temperatures in 2015.
### Plotting the graph
The record high and low temperatures are plotted as two separate lines and the area between them is shaded.
The points in the 2015 data where the ten-year record (2005–2014) for highs or lows was broken was identified and marked as scatter plot.
The temperature given in tenths of degrees C is converted back to degree C and plotted.

