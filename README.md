# car-sharing-analysis
Google Analytics Capstone Project using Car Sharing Company data.

This Case Study was completed as part of the Google Data Analytics Professional Certificate.

Objective (Ask Phase)
The objective of this data analysis project is to gain insights into car repair and maintenance needs based on general car information, rider and driver data. To achieve this objective, we need to answer the following questions:

Are there any patterns in rider/driver behavior that are correlated with repair needs?
What are the most common types of repairs needed for different car models?
What are the most common car models used by riders and drivers?
How does the age of a car impact repair needs?
Are there any trends in the type of repairs needed based on fuel type?


Prepare Phase
This data is a part of the kaggle competition dataset.
In this step, we will gather the necessary data and perform initial data cleaning. The data we have includes:

```car_train.csv``` - General car information: This includes information on the car model, fuel type, and year of production.
```sh
* car_id - car identification number
* model / car_type / fuel_type - model, type and fuel(gas, diesel) 
* car_rating / riders - rating and total number of rides by the end of 2021 year.
* year_to_start / year_to_work - year of production and year started working 
* main_city - city
```
```fix_info.csv``` - car repair and maintenance reports; This includes information on the type of repairs needed for each car and the damage degree.
```sh
* worker_id / car_id - car identification number
* work_type / work_duration - work type and duration (in hours)
* destroy_degree - the degree of wear / level of damage
* fix_date - repair date
```
```driver_info.csv``` - driver's profile information: This includes information on riders and drivers, such as age, gender, user_rating and driving history.
```sh
* user_id / age / sex - socio-demographic variables
* user_rating - driver's rating by the end of 2021
* user_rides - total number of rides in 2021 year
* user_time_accident - number of car accident
* first_ride_date - first ride date
```

Process Phase
In this step, we will perform data cleaning and data transformation to prepare the data for analysis. This includes:

- Cleaning and formatting the data to ensure consistency and accuracy.
- Combining the car information with the repair and driver data to identify any patterns or correlations.
- Removing any outliers or irrelevant data.

Analyse Phase
In this step, we will use statistical and analytical tools to analyze the data and answer the questions posed in the objective. This includes:

- Identifying the most common car models used by riders using frequency analysis and correlation analysis.
- Analyzing how the age of a car impacts repair needs using regression analysis and time series analysis.
- Identifying the most common types of repairs needed for different car models using cluster analysis and decision tree analysis.
- Identifying any trends in the type of repairs needed based on fuel type using correlation analysis.
- Analyzing patterns in driver behavior that are correlated with repair needs using correlation analysis and regression analysis.

Share Phase
- Creating visualizations and reports to communicate the analysis results clearly and effectively.
- Presenting the findings to management and other stakeholders.
- Soliciting feedback and addressing any concerns or questions.
Visualisations were created using Tableau. Published here https://public.tableau.com/views/

Act Phase
In this final step, we will take action based on the findings and recommendations from the analysis. This includes:
A powerpoint presentation was compiled .pptx.

