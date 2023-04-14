# Credit_Risk_Analysis

Realizing a credit risk analysis 

# The main objective of this project is to apply machine learning to solve a real-world challenge such as credit card risk. Starting from the credit card dataset form LendingClub - a company that provides lending services - we were able to train and evaluate models with unbalanced classes. On one hand, there were used imbalance_learn libraries and  on the other hand, the scikit_learn libraries, tools that facilitated the  building and the evaluation of the models through resampling.


 
## Results of the analysis
    After using six different machine learning models, we have obtained the following results:
    
  - Naive Random Oversampling - the accuracy test it 67%, the precision for the high_risk has a very low positivity at 1% and the recall is 74%
    https://github.com/DianaPrescura/Credit_Risk_Analysis/blob/main/Naive_Random_Oversampling.png
  
  - SMOTE - the accuracy score is 66.2%, the precision for the high_risk loans has a low positvity again at 1% and recall is 69% overal
    https://github.com/DianaPrescura/Credit_Risk_Analysis/blob/main/Smote.png
    
  - Undersampling - thebalanced accuracy score is 66.2% overall, the precision is at 99% and the recall is 41%

    https://github.com/DianaPrescura/Credit_Risk_Analysis/blob/main/Undersampling.png
  - Combination (Over and Under) Sampling - balanced accuracy score is 54.7% the precision is 99% and the recall is 57% overall

    https://github.com/DianaPrescura/Credit_Risk_Analysis/blob/main/Over%20and%20Under%20Sampling.png
  - Balanced Random Forest Classifier - the accuracy score is 77.2% the precision is 99% and the recall is 88%
    https://github.com/DianaPrescura/Credit_Risk_Analysis/blob/main/Balanced%20Random%20Forest%20Classifier.png
  - Easy Ensemble AdaBoost Classifier - the accuracy score is 91.7% the precision is 99% and the recall is 94%
    https://github.com/DianaPrescura/Credit_Risk_Analysis/blob/main/Easy%20Ensemble%20AdaBoost%20Classifier.png



Summary
Summarizing this report, based on the different techniques we have utilized, importing different libraries, we wanted to determine which model has a better accuracy score. In other words, what models that were resampled can predict with a better accuracy which loans are high risk and wich one are low risk. Analysing the results, for the given credit card data set, we cand affirm that the most accurate model is the easy Ensemble Adaboost CLassifier, with the highest precision - 99% and the highest recall - 94%
