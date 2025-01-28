# Phone Plan - Data Classification
This project is to analyze customer behavior of Megaline users. A model was developed that would analyze subscribers' behavior based on the legacy plans and recommend one of Megaline's newer plans: Smart or Ultra. As this is a classification problem between two plans, the different classification models used are Decision Tree Classifier Model, Logistic Regression Model, and Random Forest Classifier Model. 

## To Run

1) Clone the project
```
git clone https://github.com/filzamazahir/PhonePlan-DataClassification.git
```
Make sure to have pip installed, then do 
```
pip install -r requirements.txt
```
Run ```phoneplan_dataclassification.ipynb```

## Results
Based on the models developed, Decision Tree Classifier model should be used to recommend the newer plans to Megaline customers. It gave an accuracy of 0.799, which is higher than the Random Forest Classifier model whick gave an accuracy of 0.78. In addition, Decision tree classifier also had a higher speed compared to Random Forest Classifier model. On the other hand Logistic Regression model gave an accuracy of 0.74 and did not pass the threshold set for 0.75 accuracy.
