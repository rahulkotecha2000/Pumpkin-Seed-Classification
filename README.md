# Pumpkin-Seed-Classification



DATASET: https://www.muratkoklu.com/datasets/
Citation Request :
KOKLU, M., SARIGIL, S., & OZBEK, O. (2021). The use of machine learning methods in classification of pumpkin seeds (Cucurbita pepo L.). Genetic Resources and Crop Evolution, 68(7), 2713-2726. Doi: https://doi.org/10.1007/s10722-021-01226-0

https://link.springer.com/article/10.1007/s10722-021-01226-0
https://link.springer.com/content/pdf/10.1007/s10722-021-01226-0.pdf



**Summary:**

Model name: KNN
- Initial Accuracy: 67.04%
- Accuracy Post Hyper-parameter Tuning: 71.13%
- Cross Validation Score: 44.25%
- Bagging Accuracy: 71.13%
- Best Accuracy Achieved: 71.13%
        
        
Model name: Logistic Regression
- Initial Accuracy: 73.69%
- Accuracy Post Hyper-parameter Tuning: 78.16%
- Cross Validation Score: 71.45%
- Bagging Accuracy: 78.54%
- Best Accuracy Achieved: 78.54%

        
Model name: Naive Bayes
- Initial Accuracy: 77.13%
- Cross Validation Score: 67.08%
- Best Accuracy Achieved: 77.13%

        
Model name: Decision Tree
- Initial Accuracy: 76.24%
- Accuracy Post Hyper-parameter Tuning: 79.69%
        Criterion Gini:
          - Max Depth best Accuracy- 78.28%
          - Min Samples Leaf best Accuracy- 79.82%  
        Criterion Entropy:
          - Max Depth best Accuracy- 78.28%
          - Min Samples Leaf best Accuracy- 79.18%
- Cross Validation Score: 68.23%
- Bagging Accuracy: 80.20%
- Best Accuracy Achieved: 80.2%

        
Model name: Random Forest
- Initial Accuracy: 82.64%
- Cross Validation Score: 70.53%
- Best Accuracy Achieved: 82.64%
        

Model name: Support Vector Classifier
- Initial Accuracy: 
        Kernel "rbf"- 77.91%
        Kernel "linear"- 77.39%
        Kernel "poly"- 77.01%
        Kernel "sigmoid- 63.98%
- Accuracy Post Hyper-parameter Tuning: 77.26%
- Cross Validation Score: 71.22%
- Bagging Accuracy: 77.39%
- Best Accuracy Achieved: 77.91%
        
        
Voting Classifier Accuracy: 78.17%


Boosting:
- Ada Boosting: 77.00%
- Gradient Boosting: 78.00%
- XG Boosting: 78.00%
    
    
Deep Learning- Artificial Neural Network
- Best Accuracy: 88.67%
