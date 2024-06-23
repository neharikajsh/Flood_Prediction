# Data
The data for this dataset was collected from the NOAA (https://www.ncei.noaa.gov/)

### Data Description
The dataset has the following columns:

STATE: The state where the rainfall was measured.

DISTRICT: The district where the rainfall was measured.

YEAR: The year for which the rainfall data is recorded.

JAN, FEB, MAR, APR, MAY, JUN, JUL, AUG, SEP, OCT, NOV, DEC: The amount of rainfall in millimeters (mm) recorded in each month of the year.

ANNUAL RAINFALL: The total amount of rainfall recorded in the year.

FLOOD: A binary variable indicating whether a flood occurred in the district during the year (1 = flood, 0 = no flood).

### Data Usage
The Flood Detection dataset can be used to develop flood warning systems and preparedness plans by analyzing the rainfall data and flood occurrence. The dataset can also be used to conduct research on climate change and its impact on flood occurrence in India.

### Data Limitations
The dataset only includes data from 2000 to 2010, limiting long-term analysis of flood occurrence.
The data only includes rainfall data and does not include other factors that may contribute to flooding such as topography and infrastructure.

# **Summary of LSTM Model Performance for Flood Prediction in Malaysia**

The LSTM model was trained to predict whether flooding will occur in Malaysia based on historical data. The model achieved impressive results on the test set:

### Accuracy: 
The model achieved an accuracy of 99%, indicating that it correctly predicted flood occurrences in 99 out of 100 instances.

### Precision and Recall:
Class 0 (No Flood): The precision and recall were both 99%. This means that the model correctly identified instances where flooding did not occur with high precision and recalled almost all instances correctly.
Class 1 (Flood): The model achieved perfect precision (100%) and high recall (98%) for predicting flood occurrences. This indicates that when the model predicted flooding, it was almost always correct, and it correctly identified most instances of actual flooding.

### F1-score:
The F1-score, which balances precision and recall, was 99% for both classes. This demonstrates the model's robustness in accurately predicting both flood and non-flood events.

### Confusion Matrix:
The confusion matrix shows minimal misclassifications: 85 instances were correctly classified as no flood, and 51 instances were correctly classified as flood. There were only 1 false positive (predicted flood but actually no flood) and 0 false negatives (predicted no flood but actually flood).

### Conclusion:
The LSTM model demonstrated exceptional performance in predicting floods in Malaysia, achieving high accuracy and reliability in distinguishing between flood and non-flood conditions. These results suggest that the LSTM model can be a valuable tool for forecasting flood events based on historical weather data, potentially aiding in early warning systems and disaster preparedness efforts.
