# banktelemarketing
Overview: This is the data of phone call-based marketing campaigns of a Portuguese banking institution. The classification goal was to predict if the client will subscribe to a term deposit.

Approach: To classify whether each call led to a deposit, I analyzed 18 features relating to bank clients. As the class was highly skewed (The target variable y with 88% =No and 12% =Yes), I used the model stacking method. I balanced the class for each initial model before finally using Random Tree Classifier on the probabilities from the initial models to drive final predictions. 

Dataset: https://www.kaggle.com/gobert/bank-telemarketing-moro-et-al

Packages Used:  sklearn, matplotlib, numpy, seaborn, pandas.

Software Requirements:
The code is written in Python 2 and requires the installation of following python libraries: 
•	keras 2.0.6 
•	matplotlib 2.0.2
•	NumPy 1.13.1
•	pandas 0.20.3
•	scikit-learn 0.19.1
•	tensorflow 1.2.1

Other Details:
•	The required csv files are included in the same directory.
•	For complete data use bank-additional-full-csv.csv file.

Works Cited:
Lichman, M. (2013). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.
[Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31, June 2014



