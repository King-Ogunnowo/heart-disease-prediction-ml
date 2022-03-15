# Heart Disease Prediction
## Description
This repository houses all dependencies used to predict the likelihood of heart disease with a trained model. 
## Files and Objects in the repository
1. Dataset 
2. Notebook 
## Packages Used 
1. Pandas (1.3.5)
2. numpy (1.19.5)
3. matplotlib (3.6.0)
4. seaborn (0.11.2)
5. imblearn (0.9.0)
6. Scikit-Learn (1.0.2)
7. IPython(7.29.0)
8. random
## Methodology
1. **Binary Classification**: This project is approached from a binary classification persperctive, as the purpose is do identify people who are likely or not likely to develop heart disease. 
2. **Model Evaluation**: This task makes use of the hold-out-validation set, where dataset is split into train and test sets in a 80:20 ratio. 
3. **Choosing the "right" model**: Train set will be used to train four algorithms and each model will be evaluated on the test set. These algorithms include:
  <ul>
    <li>Random Forest Classifier</li>
    <li>Gradient Boosting Classifier</li>
    <li>Decision Trees Classifier</li>
    <li>Logistic Regression</li>
</ul>
Performance on the test set for each model is measured by recall and confusion matrix.<br> 
<p>The Random Forest Classifier is chosen as model for having these results
<img width="523" alt="Screen Shot 2022-03-15 at 1 40 47 PM" src="https://user-images.githubusercontent.com/66335828/158379761-4d85d639-0469-47ff-a586-5b8ca726a968.png">
  
## Model Pipeline for Prediction
  
<img width="361" alt="Screen Shot 2022-03-15 at 1 29 08 PM" src="https://user-images.githubusercontent.com/66335828/158377853-81577ee2-ba74-4942-8a44-20cd35c84644.png">
  
Repository owner: Oluwaseyi Ogunnowo seyiogunnowo@gmail.com
