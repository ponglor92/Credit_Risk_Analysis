# Credit_Risk_Analysis

## Overview of the Analysis
The purpose of this project is to use and evaluate different types of machine learning techniques to assess individual credit risks. The dataset that will be used is from Lending CLub, a peer- to- peer lending service company. Techniques such as oversampling and undersampling will be used with the algorithms: RandomOverSampler and SMOTE, along with ClusterCentroids. Another task is to compare the machine learning models to predict credict risk. 

## Results
The results from the six different machine learning models include the balanced accuracy, precision, along with the recall scores. 

### NAIVE RANDOM OVERSAMPLING

![2022-08-11 (10)](https://user-images.githubusercontent.com/101531875/184279460-096aa399-34ec-4b59-9886-7957c70c21d4.png)
![oversampling](https://user-images.githubusercontent.com/101531875/184278547-c2cbc13c-5f55-4afc-8009-5ca9a88ebf06.png)

- Balanced accuracy score: 0.6449163069955265
- Precision: the precision for high risk is almost 1% making f1 2% because of the sensivity being at 72%. As for low risk, the precision is 100% with a sensivity of 57%.
- Recall score: As stated above,recall for high risk is 72% and for low risk it is 57%

### SMOTE Oversampling

![2022-08-11 (11)](https://user-images.githubusercontent.com/101531875/184279656-54731064-043d-4bf7-b2b4-5dd09d58ae68.png)
![2022-08-11 (12)](https://user-images.githubusercontent.com/101531875/184279674-d6e01cf3-c661-4509-8dc6-2ff679b3c2bf.png)

- Balanced accuracy: 0.6583599806425919
- Precision: precision is the same as for naive random oversampling, with high risk having a precision of 1% and low risk having a precision of 100%.
- Recall: However the sensivity is lower for high risk (63%) and a bit higher for low risk (68%)

### Undersampling:

![2022-08-11 (14)](https://user-images.githubusercontent.com/101531875/184280280-5b4e05a3-856f-447f-bf54-4f8825f951f4.png)
![2022-08-11 (13)](https://user-images.githubusercontent.com/101531875/184280305-324c941a-9b95-4a25-95ef-a448004b573d.png)

- Balanced accuracy: 0.6583599806425919
- Precision: The precision for high risk is low and higher for low risk.
- Recall: The recall for high risk is 69% putting f1 at 1% and 40% for low risk pputting f1 much higher.

### Combination (over and under) sampling

![2022-08-11 (15)](https://user-images.githubusercontent.com/101531875/184280712-eb00a74a-6622-4593-9e2b-741bda844b9a.png)
![2022-08-11 (16)](https://user-images.githubusercontent.com/101531875/184280758-839b2474-d7ff-4b07-b2bd-c1ecbc55ed07.png)

- Balanced accuracy: 0..54426617825448694
- Precision: precision is low for high_risk and high for low_risk
- Recall score: high risk has a sensiticy of 72% making f1 2% and low risk has a sensivity of 57%.

## Sumamry
Credit risk consist of a lot of information and hard to predict, even if there are many differnt linds of machine learning techniques. With the results from the machine learning techiniques above, I prefer not to use them because it could also put creditors at risk, and can't accurately predict the debtors. Most of the models did not show strong enough precision about credit risk which is the reason i would not recommend these models. 
