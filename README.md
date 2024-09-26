# SmartGrid-PowerLoadPrediction

This project analyzes load and temperature data from 20 load zones and 11 temperature 
stations across the US to explore patterns and correlations between temperature and energy load values.
The goal is to develop predictive models for load values using machine learning.

The analysis begins by examining correlations between temperature stations and load zones. 
Where strong correlations exist, temperature data from the correlated station is used for load prediction. 
In cases of weak correlations, a method is implemented to select temperature data based on factors like 
geographic proximity, climate similarity, and historical trends.

Machine learning algorithms are applied to predict load values using the selected temperature data. 
The results provide insights into how temperature affects load in different zones, informing utility 
companies about the best strategies for load forecasting and resource management. 
This research aims to improve energy management by helping utilities make more informed decisions.
