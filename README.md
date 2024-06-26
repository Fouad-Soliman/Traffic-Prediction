# Traffic Prediction
Description:
    Traffic congestion and related problems are a common concern in urban areas. Understanding traffic patterns and analyzing data can provide valuable insights for transportation planning, infrastructure development, and congestion management. 
Dataset:

    It is a valuable resource for studying traffic conditions as it contains information collected by a computer vision model. The model detects four classes of vehicles: cars, bikes, buses, and trucks. The dataset is stored in a CSV file and includes additional columns such as time in hours, date, days of the week, and counts for each vehicle type (CarCount, BikeCount, BusCount, TruckCount). 
    The "Total" column represents the total count of all vehicle types detected within a 15-minute duration. 
    The dataset is updated every 15 minutes, providing a comprehensive view of traffic patterns over the course of one month. Additionally, the dataset includes a column indicating the traffic situation categorized into four classes: 1-Heavy, 2-High, 3-Normal, and 4-Low. This information can help assess the severity of congestion and monitor traffic conditions at different times and days of the week.

The project implementation steps will go as follows:

    1- Do an Exploratory Data Analysis .
    2- Apply the required data preprocessing methods (If found).
    3- Build classification models to predict the traffic situation and compare the evaluation metrics (as accuracy, precision,F1 score and ROC curves) of various classification algorithms.
