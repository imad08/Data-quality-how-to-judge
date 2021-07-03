# Data-quality-how-to-judge
Outlier detection is an important problem with several applications.
The goal in outlier detection is to nd those data points that contain
useful information on abnormal behavior of the system described
by the data. Such data points are a small percentage of the total
population and identifying and understanding them accurately is
critical for the health of the system.
Credit card fraud detection is one such problem that is often formulated as an outlier detection problem. Credit card fraud is one of
the common type of frauds that occur in e-commerce marketplaces
and it is important to have robust mechanisms in place to detect
∗This work was done while the author worked at eBay
it in timely manner. In credit card fraud detection, the situation
aggravates by the fact that the fraudulent behavior patterns keep
changing. This is because fraudsters keep innovating novel ways to
scam people and online systems. Combination of changing patterns
and fewer labeled data points makes it an extremely challenging
problem to keep any marketplace safe and secure.

#what we did 
Implemented anunsupervised novel clusteringbased al-gorithm onann-thyroid & Credit Card Frauddetectiondataset to detect outliers based on consistency score of data.◦Obtained high precision on both dataset and Area under theprecision-recall curve (AUPRC) of 0.557 & 0.223 respectively.◦Extended the idea on hand written digit dataset after extrac-ting features from image usingResnet-50 and VGG-16

## RESNET 
ResNet uses Batch Normalization at its core. The Batch Normalization adjusts the input layer to increase the performance of the network. The problem of covariate shift is mitigated. ResNet makes use of the Identity Connection, which helps to protect the network from vanishing gradient problem. we extracted features using this architecture 
