# Flight-Delay-Data
Exploratory data on flight delay due to weather

Title: US Major Airport Weather Delay (2006-1025)
Summary: This interactive map shows the flight delays in hours at 29 US major airport during 10 years. Data was breakdown into 12 canlendar month to show delay changes through out the year.
A map is displayed and airports are shown at their geographical locations.The amount of delay are shown with circle with varying radia. The initial page clearly shows the amount of delays at different airport and their comparison. Several other interesting findings are presented as tabs on the screen.

Design:

1. Visualization types: there are one map, one bar chart and two line charts in this visualization.

Map was chosen to show the location of the airport, so the viewer can have an intuitive idea on what type of weather is expected at each airport based on its geographical location. Sized circles provides a direct presentation of amount of delay.

The bar chart was chosen to show the delay data at all airports in a more comparative way. It was chosen because it is good for categorical data comparison.

The two line charts are showing the time trend of delay. Line charts were chosen because it is good to show changes along with time.

2. Visualization encoding is as follows:

airport location: position on the map & position on x-axis;
amount of delay: radius of circle on map, bar length & point position in charts;
month: tabs to separate data by month, position of x-axis in chart;
year: position of y-axis in chart;

3. Layout:
Map: Center, shows locations of airport and delay hours as the circle size and tooltip at airport circle;
Barchart: Below the map, shows the comparison of all 29 airports in the decending order;
Line Chart 1: Upper right, shows the delay change across all months of the year for comparison.
Line Chart 2: Middle right, shows the delay change across years for average or a specific month.

4. Exploratory findings are presented as tabs on the top section of the page.

5. The narrative structure is viewer driven, explorative style;



Feedbacks:

### feedback 1:
1. Title font too big (solution: font changed)
2. Map too small (Solution: map rescaled)
3. Need to see actual data (solution: tooltip added)

### feedback 2
1. Better to have a button for Total (solution: total added)
2. Like to see comparison of data of all month.(solution: month data are plotted with line chart.)
3. Need to see weather delay across all years. (solution, Yearly chart was added)

### feedback 3
1. The circle of total delay too big, and hard to compare. (solution: instead of total, showing average monthly)
2. Better to associate map location with chart. (Red highlighted bar while clicking on airport)

### Reviewer:
1. Exploratory findings need to be added. (solution: Some findings were added as tabs above the charts, and corresponding map and charts are highlighted to draw attention.)


Please note:

the first version of file is named: index_old.html
the 1st sumbmission is named: index_1st.html
the 2nd sumbission is named: index_2nd.html
the latest is named: index_new.html

Resources:
1. http://stat-computing.org/dataexpo/2009/supplemental-data.html
2. http://www.transtats.bts.gov/
3. stackoverflow.com
4. bl.locks.org

data files used:
airports.csv
flight_delay.csv
USA.geo.json

