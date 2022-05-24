# mnist_classification

This is one of the projects I work on as I follow Aurelien Geron's Hands-On Machine Learning with Scikit-Learn, Keras and TensorFlow, Copyright 2019 Aurélien Géron, 978-1-492-03264-9. You can get yourself a copy of the book [here](https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1491962291).

This project looks at the a supervised learning task, classification. MNIST data on various digits are examined to correctly predict the right number. Many types of classification, including single binary, multiclass, multilabel and multioutput classifications are examined.

## The Dataset

MNIST dataset a set of 70,000 small images of digits handwritten by high school students and employees of the US Census Bureau. Each image is labeled with the digit it represents.

## Code and Resources Used 
**Python Version:** 3.7  
**Packages:** pandas, numpy, sklearn, matplotlib  
**ML Book:** https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1491962291


 ## Training Process

   ### Training a binary classifier
    
  * STOCHASTIQUE GRADIENT DESCENT
  * RANDOM FOREST ALGORITHM
   
   ### Multiclass clasification
   
  * Support Vector Machine
  * OneVsOne Classifier
  * OneVsRest Classifier
   


 ## Performance Measures

   * Cross Validation
   * Confusion Matrix
   * Precision 
   * Recall 
   * F1 score
   * Precision/Recall Trade-off
     

## Results 

Afer scaling the inputs, I have obtain an accuracy above 89% using a SGDClassifier, but I could have obtained an 97% accuracy if my PC was able to perform a Grid Search on the KNeighbors Classifier. 
