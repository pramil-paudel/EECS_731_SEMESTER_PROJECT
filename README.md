# EECS_731_SEMESTER_PROJECT
This project is accident severity prediction based on the historical data of US Accident. This project is written/created for the partial fullfilment of course work EECS_731. 

### HOW TO OPEN PROJECT 
* It is highly recomended to open reports folder as some of the graphs are not rendered by Github. There are notebooks in PDF format to look in more details. 
### PROJECT MEMBERS 
* PRAMIL PAUDEL
* SUMIT BHATTARAI
----
### DATA_SOURCE
The data used in this project from 
* Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, and Rajiv Ramnath. “A Countrywide Traffic Accident Dataset.”, 2019.

* Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, Radu Teodorescu, and Rajiv Ramnath. "Accident Risk Prediction based on Heterogeneous Sparse Data: New Dataset and Insights." In proceedings of the 27th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems, ACM, 2019.
----
### PROJECT IDEA 
* The main idea of the project is to find relationship USA ROAD ACCIDENTS SEVERITY with different attributes.

## PROJECT LIMITATION 
* The project is limited with lots of assumption and more detail analysis. The analysis is entire based on the data available.

## CLASSIFICATION MODELS
* Decision Tree Classifiers ( GINI and ENTROPY)
* K-NN Model

## PREDICTION/REGRESSION MODELS
*
* 
## VISUALIZATION STRATEGIES 
* Visualization using ploty in USA Map upto county level
* Bar Graph, Scatter Graph etc using Pandas 

## MACHINE LEARNING MODELS 
* Decision Tree Classifier, KNN and Time Series forcasting
-----
### CODE APPROACHES
* Preprocessing of data either at start or at the beigning of the particular module.
* Entierly based on Jupyter notebook.
* No any different front End engines are used. 

### RAW DATA INFORMATION
* No of columns : 49 

**ID**

This is a unique identifier of the accident record.

text\_format

**Source**

Indicates source of the accident report (i.e. the API which reported the accident.).

grid\_3x3

**TMC**

A traffic accident may have a Traffic Message Channel (TMC) code which provides more detailed description of the event.

grid\_3x3

**Severity**

Shows the severity of the accident, a number between 1 and 4, where 1 indicates the least impact on traffic (i.e., short delay as a result of the accident) and 4 indicates a significant impact on traffic (i.e., long delay). Note that severity reported by different sources may differ in their underlying impact on traffic, so please separate data from different sources when doing severity-based analysis.

calendar\_today

**Start\_Time**

Shows start time of the accident in local time zone.

calendar\_today

**End\_Time**

Shows end time of the accident in local time zone. End time here refers to when the impact of accident on traffic flow was dismissed.

grid\_3x3

**Start\_Lat**

Shows latitude in GPS coordinate of the start point.

grid\_3x3

**Start\_Lng**

Shows longitude in GPS coordinate of the start point.

vpn\_key

**End\_Lat**

Shows latitude in GPS coordinate of the end point.

vpn\_key

**End\_Lng**

Shows longitude in GPS coordinate of the end point.

grid\_3x3

**Distance(mi)**

The length of the road extent affected by the accident.

text\_format

**Description**

Shows natural language description of the accident.

grid\_3x3

**Number**

Shows the street number in address record.

text\_format

**Street**

Shows the street name in address record.

text\_formatSide

Shows the relative side of the street (Right/Left) in address record.

text\_format

**City**

Shows the city in address record.

text\_format

**County**

Shows the county in address record.

text\_format

**State**

Shows the state in address record.

text\_format

**Zipcode**

Shows the zipcode in address record.

flag

**Country**

Shows the country in address record.

text\_format

**Timezone**

Shows timezone based on the location of the accident (eastern, central, etc.).

text\_format

**Airport\_Code**

Denotes an airport-based weather station which is the closest one to location of the accident.

calendar\_today

**Weather\_Timestamp**

Shows the time-stamp of weather observation record (in local time).

grid\_3x3

**Temperature(F)**

Shows the temperature (in Fahrenheit).

grid\_3x3

**Wind\_Chill(F)**

Shows the wind chill (in Fahrenheit).

grid\_3x3

**Humidity(%)**

Shows the humidity (in percentage).

**Pressure(in)**

Shows the air pressure (in inches).

**Visibility(mi)**

Shows visibility (in miles).


**Wind_Direction**

Shows wind direction.

grid\_3x3

**Wind_Speed(mph)**

Shows in miles per hour).


**Precipitation(in)**

Shows precipitation amount in inches, if there is any.


**Weather_Condition**

Shows the weather condition (rain, snow, thunderstorm, fog, etc.)

**Amenity**

annotation A POI which indicates presence of amenity in a nearby location.

**Bump**

A POI annotation which indicates presence of speed bump or hump in a nearby location.

**checkCrossing**

A POI annotation which indicates presence of crossing in a nearby location.

**Give_Way**

A POI annotation which indicates presence of give\_way in a nearby location.

**checkJunction**

A POI annotation which indicates presence of junction in a nearby location.

**No_Exit**

A POI annotation which indicates presence of no\_exit in a nearby location.

**Railway**

A POI annotation which indicates presence of railway in a nearby location.

**Roundabout**

A POI annotation which indicates presence of roundabout in a nearby location.

**Station**

A POI annotation which indicates presence of station in a nearby location.

**Stop**

A POI annotation which indicates presence of stop in a nearby location.

**Traffic_Calming**

A POI annotation which indicates presence of traffic\_calming in a nearby location.

**Traffic_Signal**

A POI annotation which indicates presence of traffic\_signal in a nearby location.

**Turning_Loop**

A POI annotation which indicates presence of turning\_loop in a nearby location.

**Sunrise_Sunset**

Shows the period of day (i.e. day or night) based on sunrise/sunset.

**Civil_Twilight**

Shows the period of day (i.e. day or night) based on civil twilight.

**Nautical_Twilight**

Shows the period of day (i.e. day or night) based on nautical twilight.

**Astronomical_Twilight**

Shows the period of day (i.e. day or night) based on astronomical twilight.

**3513617**

unique values