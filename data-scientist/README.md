You must perform a data analysis of the dataset "dataset_for_analysis". 
The data correspond to temperature measurements of the air conditioning and geolocation system of a bus. 
The data is not labeled, but you can propose all the models you want, classification and/or prediction, 
but in all cases you must justify them through analysis.

## Requirements:
- Programming language: **Python**.
- For visualization, you can use python libraries or use professional BI tools (Power BI, Tableau, QlikView, etc)

## Suggestions
- To process geolocation data we suggest you use the **haversine** library
- With geolocation analysis you can obtain variables such as speed or km traveled.  
- You can use whatever tools you like for the labeling process, 
  but clustering or tree techniques are very useful for these tasks. 
  The most common of the clustering ones are k-means and DBSCAN, but again, 
  you can choose the ones you want. 

## We will consider the following aspects in your code:
- Try to comply with the data analysis cycle proposed below:
    1. Business Understanding
    2. Data Mining
    3. Data Cleaning
    4. Data Exploration
    5. Feature Engineering
    6. Predictive or Classification Models
    7. Data Visualization
- Code design to optimize memory use and increase execution speed.

## Description of the variables:
Measurements are made in the climate system of a bus.
- **readingTimestamp**: time in which the sensors are read.
- **latitude**: latitude where the reading was made.
- **longitude**: longitude where the reading was made.
- **tempExt**: Temperature sensor of the climate of the area or outdoor climate where the reading was made.
- **tempInt**: Temperature sensor inside the bus at the time of reading.
- **highPressure**: High pressure sensor at the outlet of the condensers.
- **lowPressure**: Low pressure sensor at the outlet of the evaporators.

## Indications:
- Create a public repository (Github, Gitlab...) and share it with us.
- In order to understand your solution, comment on the analysis you carried out to arrive at conclusions.
- Try to commit small changes frequently. We want to see how you build your code step by step.
- Let us know when you are done, of course ;-)
