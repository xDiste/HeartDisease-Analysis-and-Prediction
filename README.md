# HeartDisease-Analysis-and-Prediction

Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of 5CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common event caused by CVDs and this dataset contains 11 features that can be used to predict a possible heart disease.

This dataset contains data from patients hospitalized for presumed cardiovascular diseases. Inside, we can find both healthy patients and those with heart disease. Obviously, all the data relating to their state of health are present, as we will see later. We have chosen it because in the medical world prevention is never too much and through research it is possible to prevent and treat many diseases that could otherwise be fatal.

People with cardiovascular disease or who are at high cardiovascular risk need early detection and management wherein a machine learning model can be of great help.

## What we have done
In this project we want to analyze this dataset with the purpose of predict the probability of a person to have an heart disease/failure, as well as interpreting affected factors on patient status. To do that we choose different ML Models and we want to compare them to find the best one for our purpose. 
* Random Forest (default and tuned parameters)
* KNN (default and tuned parameters)

`
Structure of the report: Read and Correct the dataset -> Data Observation -> Execute ML models -> Comparisons
`

## Results
AUC values:
* RF: 0.8353562325524941
* RF TUNING: 0.8530161427357689
* KNN: 0.7823765020026703
* KNN TUNING: 0.823158150260954

![image](https://user-images.githubusercontent.com/62427405/153396908-0876ca0d-a21f-4520-9206-229c25c7c776.png)


In this project we prefer the Random Forest (also without tuning the parameters), remembering however that we must first execute the SMOTE function (which uses KNN) to balance the dataset, because it has a better accuracy, recall and AUC.

These data, together, give us a good overview of the goodness of this model

**How to improve**: by adding more data (medical or about individual’s life) or adding another ML model, like XGBoost and/or weighted-KNN

**Applications**: in any medical area where you want to prevent an heart disease/attack

**Dataset**: https://www.kaggle.com/fedesoriano/heart-failure-prediction

---

NB: see the .ipynb file for full report with some explanations and .pdf file for a simple presentation of the work

Work done by:
* Christian Stingone (https://github.com/ChriStingo)
* Alex Di Stefano (https://github.com/xDiste)
