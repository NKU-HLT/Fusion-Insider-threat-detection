# Fusion-Insider-threat-detection
## Dataset
The Dataset used in this work is [CMU-CERT Dataset (versions R-4.2) ](https://resources.sei.cmu.edu/library/asset-view.cfm?assetid=508099)[[1]](#1), [[2]](#2). And we use the data preprocessing method of paper [[3]](#3).

## Code runtime environment
* Run the program using ```jupyter notebook```.
## Parameter Setting

* Modify the path of the ```trainData``` and replace it with your own dataset.

* Specify in the ```LISANCOLUMNS``` which column the user attributes and department attributes are in.

* Specify in the ```LABELCOLUMNS``` which column is the label column.

* Choose the algorithm you need in the ```MODELNAME```, there are Autoencoder and Isolation Forest available.

* ```HIDDEN_NEURONS``` represents the number of neurons per layer in the AE algorithm.
* ```K``` and ```L``` are as described in the original paper. 

<a id="1">[1]</a> 
Lindauer, Brian (2020): Insider Threat Test Dataset. Carnegie Mellon University. Dataset. https://doi.org/10.1184/R1/12841247.v1 

<a id="2">[2]</a> 
J. Glasser and B. Lindauer, "Bridging the Gap: A Pragmatic Approach to Generating Insider Threat Data," 2013 IEEE Security and Privacy Workshops, San Francisco, CA, 2013, pp. 98-104, doi: 10.1109/SPW.2013.37.

<a id="3">[3]</a> 
D. C. Le, N. Zincir-Heywood and M. I. Heywood, "Analyzing Data Granularity Levels for Insider Threat Detection Using Machine Learning," in IEEE Transactions on Network and Service Management, vol. 17, no. 1, pp. 30-44, March 2020, doi: 10.1109/TNSM.2020.2967721.
