# Credit_Risk_Analysis
Build and evaluate several machine learning algorithms to predict credit risk in FinTech Firms

## Project Overview:

The project overviews the employment of different Machine Learning techniques to train and evaluate models with unbalanced classes. We have used a credit card credit dataset from LendingClub, a peer-to-peer lending services company, had oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. We have used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. We also compared the two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Nevertheless we evaluated the performance of these models and made a written recommendation on whether these should be used to predict credit risk. 

## Resources:

- Tools & Libraries: Python , Jupyter Notebook, Anaconda Navigator

- Data : Dataset from LendingClub in csv format

## Analytical Results :

- ## Naive Random Oversampling 

![Naive Random oversampling](https://user-images.githubusercontent.com/93893263/173559557-1c89fdca-6e96-4441-9741-52fbb5bb9768.png)

![image](https://user-images.githubusercontent.com/93893263/173562448-2cac00a1-8260-4a0f-ab5e-14573b64712e.png)


- ## Smote Oversampling

![Smote Oversampling](https://user-images.githubusercontent.com/93893263/173562738-df27ec91-7408-4a25-91c5-d141e12a51ce.png)

![image](https://user-images.githubusercontent.com/93893263/173562995-08383d1e-e4ad-4e99-b40f-eea970515fa4.png)


- ## Undersampling

![Undersampling](https://user-images.githubusercontent.com/93893263/173563242-aeaf1ab6-20f0-49e1-b4f1-3f33c013098f.png)

![image](https://user-images.githubusercontent.com/93893263/173563420-9eab88eb-2686-445a-abfe-c4a6fb11e2e1.png)


- ## Combination(Over & Under) Sampling:

![Combination of Over   Under sampling](https://user-images.githubusercontent.com/93893263/173563644-650c9ed7-e961-4347-950c-5e0c5d0664d9.png)

![image](https://user-images.githubusercontent.com/93893263/173563828-ca4b9fa9-a176-46a1-a4d8-f84418349d35.png)


- ## Balanced Random Forest Classifier

![Balanced Random Forest classifier](https://user-images.githubusercontent.com/93893263/173564042-21c5c070-8386-4372-abb6-a855fc328f48.png)

![image](https://user-images.githubusercontent.com/93893263/173564244-c6ebb2d6-f1ff-4b5e-9386-a12312b76a44.png)


- ## Easy Ensemble AdaBoost Classifier

![image](https://user-images.githubusercontent.com/93893263/173567586-e6b9e92d-a7ef-41d3-b543-530a1fc81b8b.png)

![image](https://user-images.githubusercontent.com/93893263/173567847-60846755-32e3-4950-a07a-92393ec2a0e0.png)


## Project Summary

Apperently, the Easy Ensemble AdaBoost Classifier model perfomred better than all the models used in this project. Rest of the models exibits a weak precision in determining the credit risk, especially when a credit risk is high. However, the Ensemble models promises a good scope of improvemnet in credit risk analysis. Both these models are with high accuracy scores, precision and sensitivity and ideally recommended to predict credit risk.























