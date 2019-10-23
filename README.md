# Flood-Prediction

Problem stament:

Disaster prevention and prediction Flood prediction using machine learning approach.

Proposed solution:

1)PREDICTION: APPROACH 1: A dataset with the amount of rainfall and if a flood had occured in a particular area/state/city, in the previous years, will be used. The dataset will have the rainfall data for a duration of 3 months approx.

Using this dataset, we take average rainfall for every 10 days and plot it on a graph to visualize it. We take this average data of rainfall, as input to our machine learning model and if it causes a flood or not as the output labels. We train our model and save it.(depending on some threshold value of average rainfall in the dataset)

Given the input data, for consecutive 10 days, we give this data as an input, and let the model predict, if whether there is a possibility of flooding or not, by setting some threshold in the training data. Our basic approach for this problem is binary classification, using basic machine learning algorithms(linear regression or logistic regression).

This approach can be made real time prediction and accuracy can be improved with adding more features such as the type of land in that area, the location of the area etc.

APPROACH 2: There is an official website called www.india-water.gov.in , which updates itself regularly saying whether the water level in a particular area is 1)above normal flood, 2)severe flooded or 3)extremely flooded (with yellow,orange and red colour respectively).

We plan to scrap data out from this webpage from time to time and store it in a database.

2)SENDING WARNING: The database will be accessed and red alert warning will be sent to the mobile phones of all the people in the effected area, using a free online text message sending portal.

### Useful Links

#### Literature Review
  
● https://docs.google.com/document/d/1HM4hRz3Bl4w9g63J4xWnjVuJba_rgmpCyf-2O4huqaM/edit

● https://github.com/rajatkeshri/Flood-prediction

● https://www.mdpi.com/2073-4441/10/11/1536/htm


### PAPERS

● https://www.sciencedirect.com/science/article/pii/S2214241X15001212

● https://ieeexplore.ieee.org/abstract/document/8546257

● https://link.springer.com/article/10.1007/s12650-017-0453-3

● https://ieeexplore.ieee.org/document/8674113

● https://ieeexplore.ieee.org/document/8743796
