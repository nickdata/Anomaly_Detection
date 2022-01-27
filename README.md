# Anomaly_Detection
In this repository I will evaluate the results of some of the commonly used and promising Anomaly Detection methods with the Forest Fire Dataset.

**Introduction:** Outliers/Anomalies can skew the data distributions resulting in incorrect representation of the data and its relationship. Eleminating these anomalies from training data prior to model training, and prediction of the desired result, can yeild in a better fit of the data and, in turn, accurate predictions.

**Dataset:** I am using the Forest Fires Dataset obtained from UCI Machine Learning Repository. [Dataset is here](https://archive.ics.uci.edu/ml/datasets/Forest+Fires)
I have also included the dataset under the Data directory of this repo

**IDE:** Colab Notebook

**Methods:** Isolation Forest, Local Outlier Factor, and One Class SVM

**Evaluation:** I use Mean Absolute error here for model evaluation. 
To evaluate and compare the Anomaly Detection methods I use scatter plot(matplotlib). You can find all the graphs under the Plots directory of this repo. 
![Outlier Detection](https://github.com/nickdata/Anomaly_Detection/blob/main/Plots/OutlierDetectionInTemperatureData_usingIsoForest.png)
