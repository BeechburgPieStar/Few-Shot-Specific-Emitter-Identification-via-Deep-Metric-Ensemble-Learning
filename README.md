# Radio-Frequency-Fingerprinting: Few-Shot-Specific-Emitter-Identification-via-Deep-Metric-Ensemble-Learning
The code is about Few-Shot-Specific-Emitter-Identification-via-Deep-Metric-Ensemble-Learning under review

Requirements: keras=2.1.4, tf=1.14.0

Paper: http://arxiv.org/abs/2207.06592

A brief introduction to this code:
1. STC-CVCNN_Train: train feature embedding on auxiliary dataset of 90 classes, and visualization based on test dataset of 10 classes
2. STC-CVCNN_Test: train LR classifer with few-shot training dataset (1-5-10-15-20 shots), and test it on test dataset. Here, this code executes 1000 times, because different few-shot training datasets have different performance.
3. STC-CVCNN_SC: get silhouette coefficient

Model weight is given in Model/
 
Dataset: https://pan.baidu.com/s/1mca2YPeCqjvsXxOTLqVNhA, passwd: 4fhn


#The future works: Distributed learning for FS-SEI
