# Data Quality: How to Judge
Outlier detection in a dataset is an important problem with several applications. The goal in outlier detection problem statements are to find those data points that contain useful information on abnormal behavior of the system as described by the data. Such data points are a small percentage of the total population, therefore identifying and understanding them accurately is critical for the health of the system.
Credit-card fraud detection is one such case that is often formulated as an outlier detection problem. Credit-card fraud is one of the most common type of frauds that occur in e-commerce marketplaces and it is important to have robust mechanisms in place to detect such malpractices. In credit card fraud detection, the situation aggravates by the fact that the fraudulent behavior patterns keeps changing. This is because fraudsters keep innovating novel methods to bypass the online mechanisms of checks and balances put inplace by the authorities, and scam people. The combination of changing patterns and fewer labeled data points makes it an extremely challenging problem to keep any marketplace safe and secure.

The research paper was written while the authors worked at eBay in timely manner

## Our Contribution
What we did was to implement an novel unsupervised clustering-based algorithm on ann-thyroid & credit-card fraud detection dataset to detect outliers based on consistency score of data. We obtained high precision on both datasets and area under the precision-recall curve (AUPRC) was 0.557 & 0.223 on the ann-thyroid and credit-card fraud detection dataset respectively. We further extended the idea on hand written digit dataset after extracting features from image using Resnet-50 and VGG-19.

## RESNET 
ResNet uses Batch Normalization at its core. The Batch Normalization adjusts the input layer to increase the performance of the network. The problem of covariate shift is mitigated. ResNet makes use of the Identity Connection, which helps to protect the network from vanishing gradient problem. we extracted features using this architecture 
