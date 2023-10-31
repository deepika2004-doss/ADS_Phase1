# AIR QUALITY ANALYSIS AND PREDICTION IN TAMILNADU  
          Air quality analysis and prediction are crucial components of environmental science and public health management. These fields focus on monitoring, assessing, and forecasting the quality of the air we breathe, with the ultimate goal of improving air quality and minimizing its adverse effects on human health and the environment.
         Air quality analysis involves the collection and examination of data related to various pollutants present in the Earth's atmosphere, such as particulate matter (PM2.5 and PM10), ground-level ozone (O3), nitrogen dioxide (NO2), sulfur dioxide (SO2), carbon monoxide (CO), and volatile organic compounds (VOCs). Monitoring stations, satellite technology, and specialized instruments continuously measure these pollutants to generate real-time data.
          
# Dataset Information

Dataset link: https://tn.data.gov.in/resource/location-wise-daily-ambient-air-quality-tamil-nadu-year-2014  

The dataset contains all details about the quality of air in Tamil Nadu which is for predicting the quality of Air.
Where the air contains S02,NO2,etc., which helps us to analyze the Air quality in various cities of Tamil Nadu.

# Attribute Information:

<li>1.Sample: Unique identifiers for data measurements.
<li>2.State: Denotes Tamil Nadu as the data's geographical origin.
<li>3.City: Names of cities in Tamil Nadu where monitoring occurred.
<li>4.Location of Monitoring Station: Specific addresses or locations of monitoring stations.
<li>5.Agency: Organizations responsible for data collection and analysis.
<li>6.SO2 (Sulfur Dioxide): Concentrations of sulfur dioxide, a harmful gas from combustion.
<li>7.NO2 (Nitrogen Dioxide): Levels of nitrogen dioxide, an air pollutant from various sources.
<li>8.RSPM10 (PM10): Measurements of particulate matter with a diameter of 10 micrometers.
<li>9.PM 2.5 (Particulate Matter 2.5): Data on fine particulate matter with a diameter of 2.5 micrometers, posing health risks.

# Libraries

<li>pandas
<li>matplotlib
<li>seaborn

# Working Procedure :

 To load and preprocess the Air Quality dataset in 2014 from Kaggle, we can use the following steps:
<li>Step 1:
Install the necessary Python libraries
<li>Step 2 :
Load the dataset
<li>Step 3 :
Explore the dataset
Print the average of the of the given columns
Print the basic information about the dataset
<li>Step 4 :
Preprocess the data
Handle missing values: There are no missing values in the dataset.
<li>Step 5 : 
Scale the numerical features
Define a function to scale numerical features
<li>Step 6 : 
Split the dataset into training and test sets.
<li>Step 7 :
Using matplotlib to visualize the air quality with Histogram.
          
# Conclusion:
We have now loaded and preprocessed the Air Quality Analysis dataset for analysis. Data Visualisation libraries to visualize the SO2,NO2 and RSPM/PM Levels.
