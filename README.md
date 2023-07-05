# Imbalanced-Semi-or-Self-Supervised-Learning

This repository contains the implementation of Semi/Self supervised Learning on Imbalanced Datasets of the research paper, Rethinking the Value of Labels for Improving Class-Imbalanced Learning Yuzhe Yang, and Zhi Xu 34th Conference on Neural Information Processing Systems (NeurIPS), 2020.  

**Repository**: https://github.com/YyzHarry/imbalanced-semi-self  
refer the above repository for base code and in-depth details.  
  
Summary and Explanation can be found in our reports.  
  
This repo, implementation of the research paper is the part of our coursework, Big Data Analytics.  

***Key Takeaways***:    
  
Two point of views are considered in the research paper.  
1. Supervision from labels typically leads to better results than its unsupervised counterparts.  
2. Heavily imbalanced data naturally incurs “label bias” in the classifier.    
  
These view points are tested using semi-supervised and self-supervised pretrained models(like ResNet32 and ResNet50, on the famous datasets CIFAR-10-LT, CIFAR-100-LT, CIFAR-10-LT,SVHN, IMAGENET and INATURALIST datasets.  

***Observations***:   
1. Positively, imbalanced labels are valuable: given more unlabeled data, the original labels can be leveraged with the extra data to reduce label bias in a semi-supervised manner, which greatly improves the final classifier.  
2. Negatively however, imbalanced labels are not useful always: classifiers that are first pre-trained in a self-supervised manner consistently outperform their corresponding baselines.  
