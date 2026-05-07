# CS-130 Project Methedology

## Data Source

- [Weather Dataset](https://corgis-edu.github.io/corgis/csv/weather/)

- The dataset above is from a github that holds a collections of dataset on a variety of topics.

- The dataset contains logged weather data from various areas in the United States. The weather data which was logged is, precipitation data, temperature data, wind speed data, and location data. 

## Data Preparation and Cleaning

- **In the data preparation and data cleaning phase I did as follows:**

    - I used the .describe() and .value_counts() functions to get a better understanding of the data that was going to manipulate and visualize.

    - Grouped each data series that I was going to visualize with the month number that each data entry was associated with.

    - Instead of taking a sliced portion of the data set I kept the dataset whole because it only represents 2 years of weather data.

    - The data set columns that I focused on are:
        - Data_Precipitation
        - Data_Wind_Speed 
        - Data_Temperature_Max_Temp
        - Date_Month

    - For the precipitation calculation I took the sum of all precipitation from the entire dataset and represented it in the visual based on total rain per month.

    - For the wind speed calcuation I took the mean/average of the entire dataset and in the visual it is represented as the wind average by month.
    
    - For the temperature calcucation I took the max temperature from each day because I think that it represent temperature fluxuation better. In the visual it is the mean/average of the max temperature of all of the days in each month. 




## Assumptions

- **While working on manipulating the data in the dataset some assumptions were made to interpet data more clearly.**

    - I assumed that if the value of precipitation is 0.0 indicates no rainfall that night.

    - Another assumption that I was that the number that the months were logged as were in correlation to their number on a calender.

    - I assumed precipitation was measured in the unit of 
    inches.

    - I asssumed wind speed was measured in miles per hour.

    - I also made the assumption temperature was measured in degrees fahrenheit.


## Limitations

- **While working with the weather data set, there were some limitations that created some difficulty analyzing data.**

    - The data set logged the month field in numerical values rather than the month name, so in visuals the month is show rather than name.

    - The Range of time that the data was collected over was only 2 years, results will only reflect weather over short amount of time which carries less accuracy.

    - All of the data collection stations did not report and eqaul amount of data. Results may be skewed do to over representations of some locations.

    - When analyzing rain totals, temperature averages, and wind averages, extraordinary weather is not properly represented.