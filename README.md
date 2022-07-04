
# ML Classifications Algorithms Implementation

---

ML model for Loan applicatoins. 
This repository contains 4 different Machine Learning Algorithms Implementation.

 
Following are the algorithms:
- k-Nearest Neighbour
- Decision Tree
- Support Vector Machine
- Logistic Regression

The results is reported as the accuracy of each classifier, using the following metrics when these are applicable:

- Jaccard Index
- F1- Score
- Logloss


## About Dataset


Historical data for Loan applications. Has customers whose loan are already paid off or defaulted.

| Fields |	Description |
| --- | --- |
Loan_status |	Whether a loan is paid off on in collection
Principal |	Basic principal loan amount at the
Terms |	Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule
Effective_date |	When the loan got originated and took effects
Due_date |	Since it’s one-time payoff schedule, each loan has one single due date
Age |	Age of applicant
Education |	Education of applicant
Gender |	The gender of applicant


### Finding Best Value for K in KNN

![App Screenshot](https://github.com/hellfire95/Classification-Algo-On-Loan-Dataset/blob/master/Best%20value%20of%20K.png?raw=true)


### Visualization
![App Screenshot](https://github.com/hellfire95/Classification-Algo-On-Loan-Dataset/blob/master/Visualization%201.png?raw=true)

![App Screenshot](https://github.com/hellfire95/Classification-Algo-On-Loan-Dataset/blob/master/principal%20visualization%202.png?raw=true)

![App Screenshot](https://github.com/hellfire95/Classification-Algo-On-Loan-Dataset/blob/master/days%20visualization3.png?raw=true)

From the above graphs we conclude that at the end of the week has highest collection amount.
## Report 

| Algorithm | Jaccard | F1-score | LogLoss |
| --- | --- | --- | --- |
| KNN | 0.718 | 0.74 | NA |
| Decesion tree |	0.742 |	0.74 | NA |
| SVM |	0.85 |	0.79 |	NA |
| Logistic Regression |	0.78 |	0.69 |	0.6009 |


