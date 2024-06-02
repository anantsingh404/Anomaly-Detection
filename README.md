# Anomaly Detection IoT23
## Data Preprocessing
This file is the data preprocessing for IoT-23 dataset. It loads 23 datasets seprately into Pandas dataframe, then skip the first 10 rows (headers) and load the 100,000 rows after. When finished, it combines 23 dataframes into a new dataset:  
iot23 combined.csv  
  
## Models
There are total of 4 models are implemented in this project:  
* CNN
* SVM
* Decision Trees
* Navie Bayes
  
## Environment Settings
Anaconda Jupyter Notebook  
Python 3.8  
Tensorflow 2.4  
  
## IoT-23 Dataset  
Stratosphere Laboratory. A labeled dataset with malicious and benign IoT network traffic. January 22th. Agustin Parmisano, Sebastian Garcia, Maria Jose Erquiaga.  
https://www.stratosphereips.org/datasets-iot23
