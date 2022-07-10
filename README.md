# PyBer_Analysis
Visualizing data using Python in Jupyter Notebook

## Project Overview
The purpose of this project is to analyze all the "PyBer" rideshare data from January to early May of 2019 and create compelling visualizations. Use Python and Pandas to create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type, along with written report that summarizes how the data differs by city type and how those differences can be used by decision-makers.

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Python 3.7, Jupyter Notebook, 1.68.1

## Results
Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

### Summary DataFrame for Urban, Suburban, and Rural ride-sharing data
<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Total Rides</th>
      <th>Total Drivers</th>
      <th>Total Fares</th>
      <th>Average Fare per Ride</th>
      <th>Average Fare per Driver</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Rural</th>
      <td>125</td>
      <td>78</td>
      <td>$4,327.93</td>
      <td>$34.62</td>
      <td>$55.49</td>
    </tr>
    <tr>
      <th>Suburban</th>
      <td>625</td>
      <td>490</td>
      <td>$19,356.33</td>
      <td>$30.97</td>
      <td>$39.50</td>
    </tr>
    <tr>
      <th>Urban</th>
      <td>1,625</td>
      <td>2,405</td>
      <td>$39,854.38</td>
      <td>$24.53</td>
      <td>$16.57</td>
    </tr>
  </tbody>
</table>
</div>

![image_name](analysis/Pyber_fare_summary.png)


## Summary
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

