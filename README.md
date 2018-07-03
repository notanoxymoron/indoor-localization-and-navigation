### This project is used study a classification problem using a dataset in the UCI machine learning repository and demonstrate the use of various classification models on the dataset. 
The complete project report can be found [here](https://github.com/dbrownambi/indoor-localization-and-navigation/blob/master/Project%20Report.pdf)

The dataset used for this project is the [BLE RSSI Dataset for Indoor localization and Navigation](https://archive.ics.uci.edu/ml/datasets). This is a multivariate classification problem. The dataset contains RSSI readings gathered from an array of Bluetooth Low Energy (BLE) iBeacons in a real-world and operational indoor environment for localization and navigation purposes.

The figure below depicts the layout of the iBeacons as well as the arrangement of locations: 
![alt text](https://github.com/dbrownambi/indoor-localization-and-navigation/blob/master/images/iBeacon_Layout.jpg "iBeacon_Layout")


The 3 classification models chosen for this project are:

1. K-Nearest Neighbors: 
2. Support Vector Machines: 
3. Random Forests:


The project traines the 3 classifiers over muliple iterations of the baseline model architecture as described in the table below:

![alt text](https://github.com/dbrownambi/indoor-localization-and-navigation/blob/master/images/arch_table.JPG "Arch_table")


Based on the final Accuracy results of the 3 classifier models, it can be concluded that Random Forests gave the best performance for this
classification problem as shown in the graph below:

![alt text](https://github.com/dbrownambi/indoor-localization-and-navigation/blob/master/images/Final_table.JPG  "Table")
![alt text](https://github.com/dbrownambi/indoor-localization-and-navigation/blob/master/images/Final_graph.JPG "Graph")
