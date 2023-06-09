# Crop-Recommendation-Using Python
Crop Recommendation - minor Project
## Problem statement
Based on predicted rainfall, soil contents and weather parameters the system will recommend the most suitable crop for cultivation. This system as contain some other feature such as display thecurrent market price and approximated yield in quintal per acre for recommended crop. Those all details will helps to farmers for choosing the most profitable crop.

Crop prediction is an essential task for the decision-makers at national and regional levels for rapid decision-making. An accurate crop yield prediction model can help farmers to decide on what to grow and when to grow.
The dataset contains following 22 crops: 
['rice', 'maize', 'chickpea', 'kidneybeans', 'pigeonpeas', 'mothbeans', 'mungbean', 'blackgram', 'lentil', 'pomegranate', 'banana', 'mango', 'grapes', 'watermelon', 'muskmelon', 'apple', 'orange', 'papaya', 'coconut', 'cotton', 'jute', 'coffee']

## Dataset
"Data_set.csv" File.

The dataset contains 2200 rows and 8 cloumns. The values of columns 1 to 7 ['N', 'P', 'K',  'Temperature', 'Humidity', 'pH', 'Rainfall'] determine the outcome - the suitable crop. The dataset contains 22 crops ['rice', 'maize', 'chickpea', 'kidneybeans', 'pigeonpeas', 'mothbeans', 'mungbean', 'blackgram', 'lentil', 'pomegranate', 'banana', 'mango', 'grapes', 'watermelon', 'muskmelon', 'apple', 'orange', 'papaya', 'coconut', 'cotton', 'jute', 'coffee'] that are recommended based on the other column values. 

* N - ratio of Nitrogen content in soil
* P - ratio of Phosphorous content in soil
* K - ratio of Potassium content in soil
* Temperature - temperature in degree Celsius
* Humidity - relative humidity in %
* ph - ph value of the soil
* Rainfall - rainfall in mm
 #### Target variable: Crop

## Model
K-Nearest Neighbor also known as KNN is a supervised learning algorithm that can be used for regression as well as classification problems. Generally, it is used for classification problems in machine learning. First, KNN is a non-parametric algorithm. KNN works on a principle assuming every data point falling in near to each other is falling in the same class. In other words, it classifies a new data point based on similarity. KNN algorithm at the training phase just stores the dataset and when it gets new data, then it classifies that data into a category that is much similar to the new data.

Working of KNN algorithm: 

1. First select the number K of the neighbors 
2. Calculate the Euclidean distance of K number of neighbors 
3. Take the K nearest neighbors as per the calculated Euclidean distance. 
4. Among these k neighbors, count the number of the data points in each category. 
5. Assign the new data points to that category for which the number of the neighbor is maximum. Model is ready 

