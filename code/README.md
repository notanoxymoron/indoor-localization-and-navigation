This project is used study a classification problem using a dataset in the UCI Machine Learning Repository and demonstrate the use of various classification models on the dataset.
The 3 classification models chosen for this project are K-Nearest Neighbors (K-NN), Support Vector Machines (SVM) and Random Forests (RF). 
As discussed in the report, this project uses 3 iterative versions of the model architecture on which the classifiers are trained.


 
#### GETTING STARTED
This project uses Jupyter notebooks with python 3.6 installed for implementing the model architectures.

Supporting libraries are:
- pandas for data structuring
- numpy for linear algebra (mostly dealing with matrices)
- sklearn for encoding and data sampling
- matplotlib for plotting quality figures and plots



#### MODELS
The folder contains 3 different Jupyter notebooks used for implementing the models:

- Baseline Model 
- Iteration-1 Model
- Iteration-2 Model

The project also contains a separate jupyter notebook that's used to visualize the Dataset named:
- Dataset Visualization



#### DATA
The dataset used for this project is the BLE RSSI Dataset for Indoor localization and Navigation found on the following website:

(https://archive.ics.uci.edu/ml/datasets/BLE+RSSI+Dataset+for+Indoor+localization+and+Navigation#)

The dataset contains RSSI readings gathered from an array of Bluetooth Low Energy (BLE) iBeacons in a real-world and operational indoor environment for localization and navigation purposes. 


#### Usage
It's recommended to use a python virtual environment. I am using anaconda with latest version of jupyter installed.



#### Conclusion
Based on the final Accuracy results of the 3 classifier models, it can be concluded that random Forests gave the best performance for this classification problem.
