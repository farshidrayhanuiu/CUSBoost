# CUSBoost: Cluster-based Under-sampling with Boosting for Imbalanced Classification

# Abstract
Class imbalance classification is a challenging research problem in data mining and machine learning, as most of the real-life datasets are often imbalanced in nature. Existing learning algorithms maximise the classification accuracy by correctly classifying the majority class, but misclassify the minority class. However, the minority class instances are representing the concept with greater interest than the majority class instances in real-life applications. Recently, several techniques based on sampling methods (under-sampling of the majority class and over-sampling the minority class), cost-sensitive learning methods, and ensemble learning have been used in the literature for classifying imbalanced datasets. In this paper, we introduce a new clustering-based under-sampling approach with boosting (AdaBoost) algorithm, called CUSBoost, for effective imbalanced classification. The proposed algorithm provides an alternative to RUSBoost (random under-sampling with AdaBoost) and SMOTEBoost (synthetic minority over-sampling with AdaBoost) algorithms. We evaluated the performance of CUSBoost algorithm with the state-of-the-art methods based on ensemble learning like AdaBoost, RUSBoost, SMOTEBoost on 13 imbalance binary and multi-class datasets with various imbalance ratios. The experimental results show that the CUSBoost is a promising and effective approach for dealing with highly imbalanced datasets. https://arxiv.org/abs/1712.04356

This is the official python implementation of the paper https://arxiv.org/abs/1712.04356 
Please cite us if you use this code.

The code is structured in a similar pattern of Sci-Kit learn. 

### for the RUSboost code 
Use fit() to train 
predict() to get predictions. 
predict_proba() and predict_proba_samme() can be used to get probabilites  

### For the LIUBoost code, 
run it as it is. A sample dataset is also provided  
